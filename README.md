# agoraaudio one to one voice

you can use it to develop cordova app.current,only has Android.

you can use the plugin by:
cordova plugin add org.apache.cordova.agoravoice --variable AGORA_ID="your agora_app_id"

start voice by 

           agoravoice.voiceChat({
                token: youtoken,
                channel: channel,
                extraString:extraString,
            },function () {
                console.log('succes');
            },function (error) {
                console.log('fail');
            })
            
            
            
