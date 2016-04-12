# parse-libraries to add to existing swift app
##### https://www.parse.com/apps/quickstart#parse_data/mobile/ios/swift/existing
---------------
#### https://www.parse.com/apps/quickstart

- add
'''
Bolts.framework, Parse.framework to project
'''

- add
'''
AudioToolbox.framework
CFNetwork.framework
CoreGraphics.framework
CoreLocation.framework
QuartzCore.framework
Security.framework
StoreKit.framework
SystemConfiguration.framework
libz.tbd
libsqlite3.tbd
'''

- replace AppDelegate.swift with the one in this directory

- compile and run
