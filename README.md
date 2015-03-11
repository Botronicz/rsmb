Really Small Message Broker - Alternative source branch.
=================

Recently I was looking for a messaging platform which I could use in my home automation project when I discovered MQTT-SN (MQTT for Sensor Networks), even lighter then its already lightweight sibling MQTT ([MQ Telemetry Transport](http://mqtt.org/)), protocol.

While there are few available MQTT brokers, it seems there is only one MQTT-SN broker called **Really Small Message Broker**, or **RSMB**, so my choice was easy.

After I experienced with RSMB I discovered couple of missing features (e.g: incomplete support of sleeping clients, pre-defined topic IDs) of MQTT-SN protocol. While MQTT features of RSMB are already incorporated into its successor [Mosquitto](http://mosquitto.org/) there is not much buzz around MQTT-SN and my personal opinion is that it is considered secondary.

Fortunately RSMB has been open sourced and its code is available on [Eclipse.org](http://git.eclipse.org/c/mosquitto/org.eclipse.mosquitto.rsmb.git) so I decided help myself, fix some bugs, add few features and and do it Open.

Hopefully couple of you will find it useful and will benefit from it.

## Expectations ##
Fix few bugs, add some features so the MQTT-SN support in RSMB will be good enough for home and small applications


## More MQTT,  MQTT-SN and RSMB ##

[MQTT-SN specification](http://mqtt.org/new/wp-content/uploads/2009/06/MQTT-SN_spec_v1.2.pdf), version 1.2. This is a document I mostly work with when figuring out how particular feature should work.

More on RSMB is in [Getting Started](rsmb/doc/gettingstarted.htm). It covers [protocol concepts](rsmb/doc/gettingstarted.htm#basics), RSMB [configuration](rsmb/doc/gettingstarted.htm#configfiles), [troubleshooting](rsmb/doc/gettingstarted.htm#troubleshooting), [bridging](rsmb/doc/gettingstarted.htm#bridging) two brokers together, etc.

Since beginning of 2015 HiveMq is running series of informative blogs [MQTT Essentials](http://www.hivemq.com/blog/).


## Credits ##
Most of credits belong to Ian Craggs from IBM UK - original maker of RSMB.

And of course other small contributors who gave hand to the project.


## License ##
[Eclipse Public License Version 1.0](https://www.eclipse.org/legal/epl-v10.html)


[![Analytics](https://ga-beacon.appspot.com/UA-57939436-3/RSMB/README?pixel)](https://github.com/igrigorik/ga-beacon)
