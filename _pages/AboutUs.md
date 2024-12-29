---
layout: about
title: About us
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
        <p>Robotics prototyping can be a tedious process with many hours being wasted debugging problems that shouldn't be of concern. SideKick provides an ecosystem in which hardware, software, and firmware are all designed to work seamlessly together to provide an easy to use platform which allows for easy debugging.</p>
        <p><span class="keyword">Hardware </span>is a key part of robotics and one of the hardest aspects to debug. <span class="keyphrase">Our STEM PCB offers an elegant all-in-one solution</span> with sensors, data logging, and many actuator-ready outputs.</p>
        <p><span class="keyword">Software </span>provides a method of displaying data.The SideKick app allows you to: display graphs in real time; output data to a terminal; record live data; manage your devices and more.</p>
        <p><span class="keyword">Firmware </span>connects everything together, it allows the robot to be controlled by hardware and output data. The ConsciOS firmware is an easy-to-use C++ framework that allows for easy state management; macros for graphing and recording data; and a selection of libraries to perform most calculations for robotics.</p>
    </div>
</div>
<div class="stem" id="STEM_info">
    <div class="row" id="stem-card">
        <div class="col-sm mt-2 mt-md-0 stem" id="stem-info">
            <div id="stem-info-2">
                <p id="stem-name">SideKick STEM</p>
                <p id="stem-description">The ultimate robotics prototyping PCB.</p>
                <a id="stem-button">
                    Find out more.
                </a>
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
    <div class="row">
        <h1>STEM</h1>
        <ul>
        <li>12 Servo Connections</li>
        <li>BMI088 Gyroscope and Accelerometer</li>
        <li>BMP280 Barometer</li>
        <li>SD Card for data collection</li>
        <li>Multi coloured statusLED</li>
        </ul>
        <p>Our robotics-focused PCB removes many common areas of debugging by providing a suite of input and output devices which are common in many robotics projects.</p>
    </div>
</div>