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
                <a id="stem-button">Find out more.</a>
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
<div class="gui" id="GUI_info">
    <div class="row" id="gui-card">
        <div class="col-sm mt-2 mt-md-0" id="gui-info">
            <h1>SideKick App</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis a erat ac elit consectetur viverra. Sed sit amet purus sed risus laoreet tincidunt. Integer volutpat fringilla risus, ut aliquet odio egestas pulvinar. Nunc in finibus massa. Phasellus consequat tempor eros eu pulvinar. Maecenas bibendum libero risus, vel sodales mi viverra vitae. Maecenas eget ornare nisl.</p>
            <p>Cras ante orci, maximus non nulla et, placerat facilisis erat. Morbi nisl mi, eleifend ut arcu rutrum, porta vehicula elit. Vestibulum finibus porttitor lacus eu vestibulum. Nullam urna ipsum, tristique quis nibh vitae, malesuada porttitor sapien. Nulla dui neque, malesuada quis commodo dictum, sollicitudin dapibus nisl. Integer ut dictum sapien. Cras hendrerit porta ante et semper. Nulla eu orci sed lectus gravida iaculis et in est. Suspendisse feugiat nunc in fringilla ornare. Etiam sit amet orci eget nisi convallis pretium. Sed sit amet placerat tortor, at viverra est.</p>
        </div>
        <div class="col-sm mt-2 mt-md-0">
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