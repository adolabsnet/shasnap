# shasnap v0.1
Take webcam shots from target just sending a malicious link

![snap](https://images.app.goo.gl/2bFy9mQ4TxtUyBpE8)

# How it works?
<p>The tool generates a malicious HTTPS page using Serveo or Ngrok Port Forwarding methods, and a javascript code to cam requests using MediaDevices.getUserMedia. </p>

[See more about MediaDEvices.getUserMedia() here](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)
<p> To convince the target to grant permissions to access the cam, the page uses a javascript code made by https://github.com/wybiral that turns the favicon into a cam stream.</p>

## Installing (Kali Linux/Termux)
git clone https://github.com/SharqanAhamed/saycheese
cd shasnap
bash shasnap.sh
