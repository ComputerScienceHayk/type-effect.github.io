![Image alt](https://github.com/ComputerScienceHayk/type-effect/blob/master/src/ezgif.com-gif-maker.gif)


#1 You need to have node js and npm on your machine.
  https://nodejs.org/en/
  
#2 init react app
  npm init react-app your-app-name
  
#3 install react-typing-effect
  npm install react-typing-effect
  more deatails here https://www.npmjs.com/package/react-typing-effect
  
#4 add this code to your component

  import React from 'react';
  import ReactTypingEffect from 'react-typing-effect';

  const ReactTypingEffectDemo = () => {
    return (
      <ReactTypingEffect
        text="Hello Little Engine" 
      />
    );
  };

#5 run "npm start" if you want to start on http://localhost:3000/
  
