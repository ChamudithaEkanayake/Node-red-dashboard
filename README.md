# Node-red-dashboard **Version 1.0**

<a name="top"></a>

Created by **Chamuditha Ekanayake**, this repository contains the complete Node-RED dashboard suite for Project VELO AI. It includes all necessary configurations and widgets for displaying and managing real-time data. Update README.md

## Table of Contents
1. [Introduction of Node-RED](#introduction-of-node-red)
    - [Overview and Features](#overview-and-features)
2. [Purpose and Applications](#purpose-and-applications)
    - [Common Use Cases](#common-use-cases)
3. [Required Hardware](#required-hardware)
    - [Minimum System Requirements](#minimum-system-requirements)
4. [Installing Node-RED](#installing-node-red)
    - [For Windows](#for-windows)
        - [Prerequisites](#prerequisites)
        - [Installing Node-RED Packages](#installing-node-red-packages)
    - [For Linux](#for-linux)
        - [Prerequisites](#prerequisites)
        - [Installing Node-RED Packages](#installing-node-red-packages)
5. [Getting Started with Node-RED](#getting-started-with-node-red)
    - [Opening Node-RED](#opening-node-red)
    - [Basic Workflow Creation and Management](#basic-workflow-oreation-and-management)





## Introduction of Node-RED

### Overview and Features

<div align="center">
    <h1></h1>
    <a href="https://wiki.seeedstudio.com/reComputer_J4012_Flash_Jetpack/">
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/2b/Node-red-icon.png"
            alt="Node-RED"
            width="400"
            height="300">
    </a>

<h4 align="justify">Node-RED is a powerful, open-source flow-based development tool for visual programming. It is primarily used for wiring together devices, APIs, and online services in new and interesting ways. Developed by IBM, it provides a browser-based editor that makes it easy to wire together flows using a wide range of nodes. Node-RED is especially popular in IoT and home automation projects for its ease of use and integration capabilities.</h4>

<h3 align="left">Key Features</h3>
<ul align="left">
    <li>Browser-based flow editor</li>
    <li>Wide range of pre-built nodes</li>
    <li>Extensible with custom nodes</li>
    <li>Integrates with various APIs and services</li>
    <li>Supports MQTT, HTTP, WebSocket, and more</li>
    <li>Flow and subflow capabilities for reusable code</li>
</ul>
</div>





## Purpose and Applications

### Common Use Cases

<div align="center">

<h4 align="left"><b>Node-RED is versatile and can be used in numerous scenarios</b></h4>
<ul align="left">
    <li><b>IoT Projects:</b> Connect and control IoT devices, gather and visualize sensor data, and automate smart home systems.</li>
    <li><b>Home Automation: </b>Manage lighting, climate control, security systems, and more from a centralized dashboard.</li>
    <li><b>Industrial Monitoring:</b> Monitor and control industrial processes, track equipment status, and visualize operational data.</li>
    <li><b>API Integration:</b> Create API workflows, connect different services, and manage data flows between them.</li>
    <li><b>Data Visualization: </b>Build real-time dashboards to visualize data from various sources.</li>
</ul>

<h1></h1>
<a href="https://wiki.seeedstudio.com/reComputer_J4012_Flash_Jetpack/">
        <img src="https://www.iqhome.org/image/cache/catalog/solutions/flowcharts/Outputs/node-red_output-2722x1080.png"
            alt="Use of Node-RED"
            width="500"
            height="300">
    </a>

</div>





## Required Hardware

### Minimum System Requirements


<h3></h3>
<h4 align="left"><b>Node-RED is versatile and can be used in numerous scenarios</b></h4>
<ul align="left">
    <li>Processor: 1 GHz or faster</li>
    <li>Memory: 512 MB RAM (1 GB recommended)</li>
    <li>Storage: 100 MB available disk space</li>
    <li>Operating System: Windows, macOS, Linux, or Raspberry Pi OS</li>
</ul>

<h1></h1>




## Installing Node-RED

### For Windows 

### Prerequisites

<div align="center">

<h4 align="left">Before installing Node-RED, you need to install <a href="https://nodejs.org/en"> <b><i>Node.js </i></b></a>  , which is the underlying platform Node-RED runs on.</h4>

<ul align="left">
    <dt>
        <strong>Download Node.js:</strong><br>
         <dd><li> Go to the <a href="https://nodejs.org/en"> Node.js </a> website and download the latest LTS version. </li></dd>
    </dt>
    </dt>
        <strong>Install Node.js:</strong><br>
        <dd><li> Follow the installation instructions for your operating system. </li></dd>
    </dt>
</ul>
<h1></h1>

</div>


### Installing Node-RED Packages

<div align="center">

<h4 align="left">Once <a href="https://nodejs.org/en"> Node.js </a> is installed, you can install Node-RED using npm (Node Package Manager).</h4>

<ol align="left">
    <li>Open a terminal or command prompt.</li>
    <li>Install Node-RED:</li>
    <pre><code> npm install -g node-red </code></pre>
    
</ol>

</div>



<br>



### For Linux

### Prerequisites

<div align="center">

<ol align="left">
    <li>Update Package Lists:</li>
    <pre><code> sudo apt update </code></pre>
    <li>Install Required Dependencies:</li>
    <ul>
        <li> Ensure you have curl installed to download Node.js setup script: </li></dd>
        <pre><code> sudo apt install curl </code></pre>
    </ul>
    
</ol>

</div>
<br>


### Installing Node-RED Packages

<br>

<div align="center">

<ol align="left">
    <li>Install Node.js:</li>
    <ul>
        <li> Install Node.js and npm from the NodeSource repository. This will also install npm (Node Package Manager): </li></dd>
        <pre><code> curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - </code></pre>
        <pre><code> sudo apt install -y nodejs </code></pre>
    </ul>
    <li>Verify Node.js and npm Installation:</li>
    <ul>
        <li> Check that Node.js and npm are installed correctly: </li></dd>
        <pre><code> node -v </code></pre>
        <pre><code> npm -v </code></pre>
    </ul>
    <li>Install Node-RED:</li>
    <ul>
        <li> Install Node-RED globally using npm: </li></dd>
        <pre><code> sudo npm install -g node-red </code></pre>
    </ul>
    
</ol>

</div>

<br>





## Getting Started with Node-RED

### Opening Node-RED


<div align="center">

<ol align="left">
    <li>Start Node-RED:</li>
    <ul>
        <li> Run the following command in your terminal: </li></dd>
        <pre><code> node-red </code></pre>
    </ul>
    <li>Access the Node-RED Editor:</li>
    <ul>
        <li> Open a web browser and navigate to <a href="http://localhost:1880">http://localhost:1880 </a> </li></dd>
    </ul>
    
</ol>

</div>


### Basic Workflow Creation and Management