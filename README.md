# TextToKeyb

zip myscript.zip myscript

base64 --wrap=0 myscript.zip > myscript.zip.b64

java -jar TextToKeyb.jar myscript.zip.b64 3000

Then in windows 

certutil -decode encodedInputFileName decodedOutputFileName
