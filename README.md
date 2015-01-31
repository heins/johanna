# JOHANNA

Visual User Interface for Things (Human User Interface for the Internet of Things)

JOHANNA is a webbased tool for easy designing and using a visual user interface for devices of the Internet of Things.

JOHANNA was inspired by TouchOSC from hexler.net, Backbone-OSC (https://github.com/kn0ll/backbone-osc) and Dashku (https://github.com/Anephenix/dashku) from Paul B. Jensen and commercial tools like Certec Ativse (http://www.atvise.com/) or Siemens WinCC flexible for industrial PLCs.

Th idea is, 

  * that you have a user interface (boards), which you can create by your self (using drag & drop of widgets), 
  * that you can create your own widgets (HTML5/CSS/Javascript/MAIER), 
  * can nest widgets inside widgets (combining widgets)
  * share these widgets over a WidgetFactory (cloud) with other users, 
  * share boards over a BoardFactory,
  * can lock widgets and boards (so you could not change the design without permission),
  * have an ACL (which user can see, use, edit the content of a widget.
  * connect the widget content with MQTT messages (instead OSC Open Sound Controll like done in TouchOSC) (Widget sends MQTT-message, message controlls widgets).
  * JOHANNA should support responsive designs
  * JOHANNA shoukd have an integrate version control system (like git).


JOHANNA should run under node.js, so you will have not to install a configurator/board editor. Both configurator and user interface are running inside a webbrowser or could be WebApps.

JOHANNA should work well with programming systems like nodeRED, noFlow or MAIER - Programmin Things.

For Charts we think about using NVD3.js.

For using JOHANNA together with other protocolls like OSC, CoAP, REST etc., you can use transformation tools like Ponte from Matteo Collina. (We think about an own tool for this, but this is future.)
