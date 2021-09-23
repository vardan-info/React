import React, { Component } from 'react';

import './App.css';

class App extends React.Component {
    state={
      curTime : new Date().toLocaleString(),
    }
    render(){
      return (
        <div className="App">
          <p>Current Time : {this.state.curTime}</p>
        </div>
      );
    }
  }

export default App;
// // import React from "react";
// // // import "./style.css";

// // // export  default class App extends Comment{
// // //   state ={
// // //     count:0
// // //   }
// // //   handlerClick(){
// // //     this.setState({})
// // //   }

// // //   render(){
// // //     const {count} = this.state
// // //     return(
// // //       <div>
// // //         <h1>{count}</h1>
// // //       </div>
// // //     )
// // //   }


// // // }

// // const arr = [26,256,13,169,39,5,7];
// // let copy = arr;
// // copy[0] = 1500;
// // console.log(arr[0]);

// // // handlerClick


// // export default function Cars (props){
// //   return(
// //     <div>
// //       {props.cars.map}
// //     </div>
// //   )
// // }

// // Cars.propsType = {
// //   cars:propsTypes.array.isRequired;


// // }

// // tiperi stugum
// // propsType.array,
// // propsTypes.bool,
// // propsTypes.funct,
// // propsTypes.number;
// // propsTypes.object;
// // propsTypes.string;
// // propsTypes.symbol

// // react-Element
// // propsTypes.element
// propsTypes.oneOf(['male', 'femaile']),

// obyekti nshvac tiper 
// date:propsTypes.oneOfType({
//   propsTypes.number,
//   propsTypes.string
// }),
const arr = [1,2,3,5,8,5,];
let [a,e,d,e,d,f] = [true,5]
