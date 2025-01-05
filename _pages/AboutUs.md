---
layout: about
title: Home
permalink: /
profile:
  align: right
  image:
  image_circular: false # crops the image to make it circular
  social: false # includes social icons at the bottom of the page
---
<div class="row" id="about">
    <div class="col-sm mt-2 mt-md-0" id="v-centered-img">
        {%  include figure.liquid
            loading="eager"
            path="assets/img/GUI_Demo.jpg"
        %}
    </div>
    <div class="col-sm mt-2 mt-md-0" id="our-vision">
        <h1>Our vision</h1>
        <p>Robotics prototyping can be a tedious process with many hours being wasted debugging problems that shouldn't be of concern. <span class="keyphrase">SideKick provides an ecosystem in which hardware, software, and firmware are all designed to work seamlessly together </span>to provide an easy to use platform which allows for easy debugging.</p>
        <p><span class="keyword">Hardware </span>is a key part of robotics and one of the hardest aspects to debug. <span class="keyphrase">Our STEM PCB offers an elegant all-in-one solution</span> with sensors, data logging, and many actuator-ready outputs.</p>
        <p><span class="keyword">Software </span>provides a method of displaying data.<span class="keyphrase">The SideKick app allows you to: display graphs in real time</span>; output data to a terminal; <span class="keyphrase">record live data</span>; manage your devices <span class="keyphrase">and more.</span></p>
        <p><span class="keyword">Firmware </span>connects everything together, it allows the robot to be controlled by hardware and output data. <span class="keyphrase">The ConsciOS firmware is an easy-to-use C++ framework</span> that allows for easy state management; macros for graphing and recording data; and a selection of libraries to perform most calculations for robotics.</p>
    </div>
</div>
<div class="stem" id="STEM_info">
    <div class="row" id="stem-card">
        <div class="col-sm mt-2 mt-md-0 stem" id="stem-info">
            <div id="stem-info-2">
                <p class="key-name">SideKick STEM</p>
                <p class="key-description">The ultimate robotics prototyping PCB.</p>
                <a id="stem-button" href="/STEM/index.html">Find out more</a>
            </div>
        </div>
        <div class="col-sm mt-2 mt-md-0 stem" id="v-centered-img">
            <div id="stem-img">
                {%  include figure.liquid
                    loading="eager"
                    path="assets/img/STEM_transparent_aura.png"
                %}
            </div>
        </div>
    </div>
</div>
<div class="gui" id="SideKick_info">
    <div class="row" id="gui-card">
        <div class="col-sm mt-2 mt-md-0" id="gui-info">
            <h1>SideKick App</h1>
            <div class="app-info">
                <p><span class="keyword">Real time data display. </span>The SideKick app offers a terminal and multiple graphs to display data for easy analysis.</p>
            </div>
            <div class="app-info">
                <p><span class="keyword">Dynamically add and control actuators. </span>Using the actuator-test feature, you can control any pwm-based actuator from your pc.</p>
            </div>
            <div class="app-info">
                <p><span class="keyword">Record and export data. </span>You can record data for later analysis and export it to a .csv format for analysis in other programs such as excel.</p>
            </div>
            <div class="app-info">
                <p><span class="keyword">Easy to read debugging. </span>While writing code for your embedded projects, errors are clearly identifiable via our terminal output. You can also enter any arduino cli command.</p>
            </div>
            <div id="gui-btn-margin">
                <a id="gui-button" href="/GUI/index.html">Find out more</a>
            </div>
        </div>
        <div class="col-sm mt-2 mt-md-0 center-img" id="gui-img-centered">
            <div class="grid-2-2">
                <div class="gui-stock">
                    {%  include figure.liquid
                        loading="eager"
                        path="assets/img/GUI_Demo.jpg"
                    %}
                </div>
                <div class="gui-stock">
                    {%  include figure.liquid
                        loading="eager"
                        path="assets/img/GUI_Demo_Actuator.jpg"
                    %}
                </div>
                <div class="gui-stock">
                    {%  include figure.liquid
                        loading="eager"
                        path="assets/img/GUI_Demo_Excel.jpg"
                    %}
                </div>
                <div class="gui-stock">
                    {%  include figure.liquid
                        loading="eager"
                        path="assets/img/GUI_Demo_Debug.jpg"
                    %}
                </div>
            </div>
        </div>
    </div>
</div>