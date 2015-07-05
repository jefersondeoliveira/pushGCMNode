var GCM = require('gcm').GCM;
var gcm = new GCM('AIzaSyDZ-GMBC7SSLPhYJDc3-mFHtQ-W9YrzPwE');

var message = {
    registration_id: 'APA91bE3jWQWgMFp7-OKL7ovFA18wc926cBmYqw6d6GgZNpqqt1Bjx7AMeYZUYxyBfCO1wRdGNxscuIdEYdTK5Ew4gd8CE9Ip6Cc2ooVv6iSf9aLqOxXeH_jMNMbQPTGAgyEiOWzMvCiRxbIdLfc1YYSzqatJol-kzv8t_AhoH9cuBnhk8gp004', // required
    collapse_key: 'Collapse key', 
    'data.mensagem': 'Nova solicitação criada',
    'data.key2': 'value2'
};

gcm.send(message, function(err, messageId){
    if (err) {
        console.log("Something has gone wrong!: "+err);
    } else {
        console.log("Sent with message ID: ", messageId);
    }
});
