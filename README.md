# pepper-javascript-example
A simple example how to use the JavaScript SDK with the pepper robot. The sample html file will connect with a pepper robot under a given ip. Then it will create a tts service. The tts service will log in the browser console the set language of the robot. After that the robot will say "Hello World!".

You have to clone the libqi-js files:

```
https://github.com/aldebaran/libqi-js.git
```

I created a user nao inside a Ubuntu 16.04 virtual machine so my import is as example:

```
<script src="/home/nao/libqi-js/libs/qi/2/qi.js"></script>
<script src="/home/nao/libqi-js/libs/qimessaging/1.0/qimessaging.js"></script>
```

As alternative you can import this libraries directly from your pepper robot with:

```
<script src="<ip_of_your_pepper_robot>/libs/qi/2/qi.js"></script>
<script src="<ip_of_your_pepper_robot>/libs/qimessaging/1.0/qimessaging.js"></script>
```
