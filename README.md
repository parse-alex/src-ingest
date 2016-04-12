# src-ingest
-----------

- parse-library-1.12.0.zip : https://www.parse.com/apps/quickstart#parse_data/mobile/ios/swift/existing
- akhmed-idigo-create-full-instagram.zip.openssl : https://www.udemy.com/create-full-instagram/learn/v4/content

#####
# parse-libraries to add to existing swift app
##### https://www.parse.com/apps/quickstart#parse_data/mobile/ios/swift/existing
---------------
#### https://www.parse.com/apps/quickstart

- file copy frameworks to project at AppDelegate.swift level
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
