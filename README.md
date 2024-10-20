# p5-flipdots
an API to allow p5.js to control a flip-dot display

![Demo](./docs/tixy_demo.gif)

## setup instructions
fire up your favorite terminal, cd somewhere comfortable and clone this repo
```
$ git clone https://github.com/yonmaor1/p5-flipdots.git
$ cd p5-flipdots
```

ensure you have [npm installed](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm). You will need npm version 16.0.0 or higher.

run
```
$ npm init -y
$ npm install body-parser@1.20.3 concurrently@9.0.1 cors@2.8.5 express@4.21.1 serialport@12.0.0
```

ensure this worked by running
```
$ npm list
```

you should see something like this:
```
p5-flipdots@1.0.0 /path/to/p5-flipdots
├── body-parser@1.20.3
├── concurrently@9.0.1
├── cors@2.8.5
├── express@4.21.1
└── serialport@12.0.0
```

to launch the program, run
```
$ node golive.js
``` 

and navigate to http://localhost:8000/ in your favorite web browser