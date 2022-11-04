# throttle
A tiny lib for throttling

## Usage
const options = { throttleId: 'aUniqueId', timeout: 2000 };
const callback = ()=>{
  console.log('Hi there!');
};
Throttle.start(callback, options);
