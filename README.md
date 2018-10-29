
# Released Key generate process

 for facebook hash key
keytool -exportcert -alias wahab -keystore "xyz.jks"| "xyzpath\openssl" sha1 -binary | "xyzpath\openssl" base64



 for shah1

keytool -list -v -keystore "xyzpath\xyz.jks" -alias "wahab"

Released Google O Client

keytool -exportcert -keystore "xyz\xyz.jks" -list -v
