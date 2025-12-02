---
layout: home
title: FPGA VGA Driver Project
tags: fpga vga verilog
categories: demo
---

Welcome to my fpga vga project this will be the blog of where i document everything that i do during my System on chip design Module Project

Last worked on 17:04 on 22/11/25.

## **Template VGA Design**
### **Project Set-Up**
This project was done in class and used verilog code to make the board connect to a monitor and from there flash lights on said monitor we did this through class i choose the change colour one as this one was probaly the best one. The image shown has my project set up you can see my tabs for the different bits of work like whats in my design sources constraints and simulation sources
<img src="https://raw.githubusercontent.com/adamokeeffee/fpga-vga-verilog/main/docs/assets/images/summary.png">
### **Template Code**
we were given basic verilog code to start with then we had to figure out what was wrong with it and get it working. they had everything we needed but was missing one bit we then worked on them and fixed the code they showed small flickers we then added a line of verilog and fixed it verilog is a analog based video not a digital video its usally 3 to 8 bits. It can be used to build 2D games and add text engines to stuff.
### **Simulation**
Explain the simulation process. Reference any important details, include a well-selected screenshot of the simulation. Guideline: 1/2 short paragraphs.
The simulation process was working on the board hooking it up to the monitor then opening the ide from there running the code and switching the monitor from hdmi to whatever the board is on making sure the code runs before anything because if it does not none of the image will appear up on the screen.  
### **Synthesis**
Describe the synthesis and implementation processes. Consider including 1/2 useful screenshot(s). Guideline: 1/2 short paragraphs.
During synthesis the Verilog code is basically translated into actual hardware that the FPGA can understand. The tool reads my VGA code figures out things like the counters comparators and registers and then turns all of that into LUTs and flip-flops. After synthesis you get a netlist which shows what the hardware will look like on the FPGA rather than just the Verilog description
### **Demonstration**
Perhaps add a picture of your demo. Guideline: 1/2 sentences.
This is my image i went for the changing colours image as i thought it was better looking than just the lines on the screen i thought they looked bland like a old tv error warning so i went with the classic rgb changing colours even tho it had more than rd green and blue it had yellow as well.
## **My VGA Design Edit**
Introduce your own design idea. Consider how complex/achievabble this might be or otherwise. Reference any research you do online (use hyperlinks).
https://www.google.com/search?q=vga+verilog+solid+color+to+lines+changing+back+and+forth&sca_esv=940aa337a8577638&sxsrf=AE3TifOhtuENvOLB4IZ9pxSL5vVSd2iOOA:1764715790456&ei=Dm0vaanKG-i-hbIPkJjiqQ4&start=40&sa=N&sstk=Af77f_cOURP2WFzpSNPMzvpd5XRagixjhtAh8p9fOU2LOCL_bSXrXlL32C_vIqjYcKPzetSgwcPTMLyctQtBTeR92RYE8RW7M9eQ0bcq_viS-dYBNZQjBS8O1hKJG0CbANjlPAsXgxr2UPzlns1f-ruy7mJ1THS7R4Zu3oJiV7t7tImEa5jdBmT1cNcnilkcfA&ved=2ahUKEwipicfO_p-RAxVoX0EAHRCMOOU4HhDy0wN6BAgLEAs&biw=1536&bih=791&dpr=1.25#fpstate=ive&vld=cid:6611e8ba,vid:DqyOiPUn_LM,st:0
For my own idea i was thinking what if i could make so that it changed between the two desings changing between solid colours and the lines this was just an idea tho i dont see how using both templates together would work.
### **Code Adaptation**
Briefly show how you changed the template code to display a different image. Demonstrate your understanding. Guideline: 1-2 short paragraphs.
### **Simulation**
Show how you simulated your own design. Are there any things to note? Demonstrate your understanding. Add a screenshot. Guideline: 1-2 short paragraphs.
### **Synthesis**
Describe the synthesis & implementation outputs for your design, are there any differences to that of the original design? Guideline 1-2 short paragraphs.
### **Demonstration**
If you get your own design working on the Basys3 board, take a picture! Guideline: 1-2 sentences.

## **More Markdown Basics**
This is a paragraph. Add an empty line to start a new paragraph.

Font can be emphasised as *Italic* or **Bold**.

Code can be highlighted by using `backticks`.

Hyperlinks look like this: [GitHub Help](https://help.github.com/).

A bullet list can be rendered as follows:
- vectors
- algorithms
- iterators

Images can be added by uploading them to the repository in a /docs/assets/images folder, and then rendering using HTML via githubusercontent.com as shown in the example below.

<img src="https://raw.githubusercontent.com/melgineer/fpga-vga-verilog/main/docs/assets/images/VGAPrjSrcs.png">
