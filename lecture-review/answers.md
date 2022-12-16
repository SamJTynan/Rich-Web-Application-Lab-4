**Props:** Value that gets passed to the component.

_function_Name(_props_) {

  return \<h2\>I am { _props_.firstname }!\</h2\>; //Display name that was passed

}

_const_ myelement = \<_Name_firstname="Sam"/\>; //Passes value into function

**State:** Value that is managed within the component itself.
{
  _const_ {useState} = React;

  _const_Count= () _=\>_ {

      _const_ [num, setNum] =useState(0);

      _const_CounterI= () _=\>_ {

         setNum (num+1); //Each time function is called value is incremented by 1

      }

      }

      return(

          \<div\>

              \<p\>Count: {num}\</p\>

              \<buttononClick={CounterI}\>Counter\</button\>

          \</div\>

      );

  }
}

**Functor:** A functor is a data structure you can map functions over and doing so modifying the contents of.

console.log([2, 4, 6].map(_x __=\>__ x_+3))

// =\> [5, 7, 9]

**Promises:**

- **Pro:** Easy error handling
- **Con:** Only one object can be returned

**Callbacks:**

- **Pro:** Easy to create asynchronous javascript code
- **Con:** Error handling difficult

**Streams:**

- **Pro:** Memory Efficiency
- **Con:** More difficult than other techniques

**CSS Box Model:** The CSS Box Model is used by browser engines as a way to define how elements are organised and displayed on the screen.

![](RackMultipart20221216-1-nmndj5_html_502f7f962dcbb944.png)

- **Content** : Content of the box, where things like texts and images are displayed
- **Padding** : The padding is an area around the content itself, and is transparent
- **Border** : Border around both the padding and the content
- **Margin** : Area outside the border, like padding is transparent
- \<!DOCTYPEhtml\>
- \<html\>
- \<head\>
- \<style\>
- div.test{
-   _background-color_: lightgrey;
-   _width_: 300px;
-   _height_: 100px;
-   _border_: 15pxsolidgreen;
-   _padding_: 50px;
-   _margin_: 20px;
- }
-
- \</style\>
- \</head\>
- \<body\>
-
- \<p\>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse ornare ultricies arcu, a fermentum metus aliquam eu. Duis arcu orci. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse ornare ultricies arcu, a fermentum metus aliquam eu. Duis arcu orci. \</p\>
-
- \<divclass = test\>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse ornare ultricies arcu, a fermentum metus aliquam eu. Duis arcu orci. \</div\>
-
- \</body\>
- \</html\>

**Bootstrapping a WebApp:**

- User navigates to URL and browser goes to Domain Name Servers
- Browser gets TCP/IP connection to server IP address and its associated port to that specific URL
- HTTP proxy accepts connection from browser after listening at that IP address
- Browser Accepts HTTP request over open TCP/IP connection
- Application server parses request and responds to browser over same connection delivering files
