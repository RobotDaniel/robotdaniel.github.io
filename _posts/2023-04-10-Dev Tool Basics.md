---
layout: post
title: Dev Tools Basics
published: true
tags: DevTools tutorials
---

This article will help you master your browser's DevTools, so you can edit websites, tweets and more


## Inspect Element
this is an essential tool for editing websites
### How To Open
use `CMD + SHIFT + C` on macOS or `CTRL + SHIFT + C` on Windows or Linux  
alternatively, you can right-click and press `Inspect`  
![Screenshot 2023-03-26 at 07 55 48](https://user-images.githubusercontent.com/101746899/228312319-aa29faeb-06c1-48d7-8aa9-27b779172bf7.png)

## The Dev Tools Menu
![Screenshot 2023-03-28 at 17 55 13](https://user-images.githubusercontent.com/101746899/228313810-ca9a52b2-da19-45df-8062-09d1bc61ada5.png)
The menu is split up into many tabs:  
`Inspector` and `Console` are the main ones we will be using  
`Inspector` lets you view the HTML of a page and edit the changes live  
`Console` allows you to view logs and use `JavaScript` commands
note:this may look slightly different on other browsers, but the functionality will be the same

## Using Inspect
I will be using `example.com` for this example, but this will work on any website or HTML document

- Step 1  
open the dev tools
- Step 2  
I would recommend making sure that this icon is highlighted  
![Screenshot 2023-03-28 at 18 16 37](https://user-images.githubusercontent.com/101746899/228317843-a0b1be7e-c4c4-4211-9b32-e68c73c781a3.png)  
this icon allows you to hover over an element and then click on it to jump to it in the inspect menu

![Screen Recording 2023-03-28 at 18 19 08](https://user-images.githubusercontent.com/101746899/228321095-eeee6266-2f56-4fd2-95ec-323f99cc689d.gif)

## Document Design mode
- step 1
open the `Console` tab   

![DocumentDesignModeStep1](https://user-images.githubusercontent.com/101746899/230598855-408f0089-65f2-4616-959a-92cbe8f96879.gif)



- step 2   
type `document.designMode = "on" ` and press enter
![DocumentDesignModeStep2](https://user-images.githubusercontent.com/101746899/230599575-1117d96b-3f24-45f6-bd53-370d19435602.gif)


this enables document design mode, you can now start editing a page by simply clicking text, you can also delete elements by selecting them  

![dev_tools_info](https://user-images.githubusercontent.com/101746899/230786311-5a1374e4-c72c-4f67-9d5f-6ad479ef72cf.gif)

## Example

### YouTube Sub Count
![SubCountExample](https://user-images.githubusercontent.com/101746899/230873710-4eabff03-2c08-4dd3-83e1-d061b17f71e6.gif)
- Step 1  
go to a YouTube Channel, e.g. https://www.youtube.com/@RobotDaniel10
- Step 2  
open the dev tools and go to the `Console` Tab 
- Step 3  
type `document.designMode = "on"` and press enter
- Step 4  
find the sub count and click on the number
- Step 5  
you should now have a text cursor on the number, you can now edit the text 

