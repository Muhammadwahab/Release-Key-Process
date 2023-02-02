
# Released Key generate process

 for facebook hash key
keytool -exportcert -alias wahab -keystore "xyz.jks"| "xyzpath\openssl" sha1 -binary | "xyzpath\openssl" base64



 for shah1

keytool -list -v -keystore "xyzpath\xyz.jks" -alias "wahab"

Released Google O Client

keytool -exportcert -keystore "xyz\xyz.jks" -list -v


 keytool -exportcert -alias buscaro -keystore "E:\NgiProjects\Buscaro Passenger\buscaro_debug.jks"| "C:\Users\Wahab\Downloads\openssl-0.9.8k_X64\bin\openssl" sha1 -binary | "C:\Users\Wahab\Downloads\openssl-0.9.8k_X64\bin\openssl" base64

for sms retrival 

set jdk enviroenment bin folder 

keytool -importcert -alias buscaro -file "C:\Users\Wahab\Desktop\deployment_cert.der" -keystore certificate.jks -storepass 123456


keytool -exportcert -alias buscaro -keystore "E:\AndroidStudio\jre\bin\certificate.jks" | xxd -p | tr -d "[:space:]" | echo -n com.buscaro.passenger `cat` | shasum -a 256 | tr -d "[:space:]-" | xxd -r -p | base64 | cut -c1-11

use these command in git bash for linux

set path=%path%;C:\Program Files\Java\jdk1.8.0_191\bin
