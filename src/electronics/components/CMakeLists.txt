SET(components_STAT_SRCS
   ecdiode.cpp
   ecsevensegment.cpp
   eckeypad.cpp
   ec555.cpp
   eccurrentsource.cpp
   ecfixedvoltage.cpp
   ecbcdto7segment.cpp
   ecsignallamp.cpp
   ecclockinput.cpp
   ecpotentiometer.cpp
   ecopamp.cpp
   ecvoltagesource.cpp
   eccurrentsignal.cpp
   ecvoltagesignal.cpp
   ecground.cpp
   multiinputgate.cpp
   fulladder.cpp
   multiplexer.cpp
   demultiplexer.cpp
   externalconnection.cpp
   ecsubcircuit.cpp
   meter.cpp
   probe.cpp
   resistordip.cpp
   addac.cpp
   dependentsource.cpp
   flipflop.cpp
   toggleswitch.cpp
   pushswitch.cpp
   ram.cpp
   discretelogic.cpp
   piccomponent.cpp
   piccomponentpin.cpp
   binarycounter.cpp
   bidirled.cpp
   matrixdisplay.cpp
   bussplitter.cpp
   matrixdisplaydriver.cpp
   magnitudecomparator.cpp
   serialportcomponent.cpp
   parallelportcomponent.cpp
   inductor.cpp
   ecbjt.cpp
   rotoswitch.cpp
   ecjfet.cpp
   ecmosfet.cpp
   variablecapacitor.cpp
   variableresistor.cpp
   capacitor.cpp
   resistor.cpp
   voltageregulator.cpp
   ledbargraphdisplay.cpp
   led.cpp
)

kde4_add_library(components STATIC ${components_STAT_SRCS})
target_link_libraries( components elements )
