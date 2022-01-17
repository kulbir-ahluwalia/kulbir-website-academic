---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Graduate Research Assistant
    company: Distributed Autonomous Systems Lab, UIUC
    company_url: ''
    company_logo: 
    location: Illinois, USA
    date_start: '2021-05-26'
    date_end: ''
    description: |2-
      Mentors:  Dr Girish Chowdhary & Dr Julia Hockenmaier
        1. Building a voice-controlled system to enable users to control a CNC based gardening robot called FarmBot remotely. We are using the Alexa API to make custom Python and Lua scripts for interfacing with the web based application of FarmBot in real-time.

        2. Working on integrating a pneumatically controlled soft robotic arm with the FarmBot to enable it to clear obstacles and harvest fruits.
        
  - title: Independent Study
    company: Robotics Algorithms & Autonomous Systems Lab, UMD
    company_url: ''
    company_logo: 
    location: College Park, Maryland, USA
    date_start: '2020-07-20'
    date_end: '2021-12-20'
    description: |2-
      Mentor:  Dr Pratap Tokekar
        1. Processed  point  clouds  of  the  pasture  obtained  from  the  gazebo  simulation  for  selected  days  of  a  yearusing LiDAR mounted on the hector quadcopter controlled using an autonomous navigation script.

        2. Automated the task of constructing gazebo worlds for grass pastures where each plant has a unique pose and is scaled to match real world height data of a location. 

        3. Our work for long-term Spatio-temporal prediction of pastures using deep learning was published in Agronomy. We used an alternative approach for forecasting long-term pasture terrains using computer vision techniques inspired by U-Net and Monte Carlo Dropout inference methods for uncertainty estimations on historical pasture data measured using LIDAR. 
        
        4. Another publication using a multi-robot deployment policy for pasture monitoring by using the predictions from spatiotemporal deep learning is under review in IEEE Transactions on Automation Science and Engineering.
      
      [[Report](https://docs.google.com/document/d/1ShAZq06kWTRoOHA_4kbe2EU6URI77JRWfvMNs_s_ylI/edit#heading=h.j3bhswj5g3i9)]  |  [[Project Code](https://github.com/precision-grazing/project/tree/main/Gazebo_evaluation)]  

  - title: Visiting Scholar
    company: University of Waterloo
    company_url: ''
    company_logo: 
    location: Ontario, Canada
    date_start: '2018-03-12'
    date_end: '2018-07-12'
    description: |2-
      Mentor: Dr Simarjeet Saini
        1. Developed an orange sweetness detector which used scaled conjugate gradient backpropagation in MATLAB to non-destructively predict sweetness of oranges using Near-Infrared spectroscopic data with an accuracy of 70\%. Discrete cosine transform was used to reduce dimensions of input matrix and prevent memory overflow.

        2. Designed prototypes in Solidworks, which were 3D printed using the Ultimaker 3. Developed low-cost photonic devices like Urea in milk detector and the Fundus eye camera. The Fundus eye camera used Raspberry Pi3 to capture images and videos of the retina of a model eye to aid in diagnosis of diseases.

        3. The Fundus eye camera was featured in an article in the Optics and Photonics News (OPN) while the orange sweetness detector was showcased in a conference presentation for sweetness prediction using Support Vector Machine as the discriminant model along with Deep Q learning to tune its parameters.

      [[Report](https://drive.google.com/file/d/1wCz3DmLyoAdq93wpnZ1DbHTxzH7V9MaT/view)]


  - title: Research Intern
    company: Indian Institute of Technology, Roorkee 
    company_url: ''
    company_logo: 
    location: Uttarakhand, India
    date_start: '2016-06-01'
    date_end: '2016-07-31'
    description: |2-
      Mentor:  Dr Dharmendra Singh
        1. Varied the thickness of radio wave absorbers such as nickel ferrite on a UAV model and its individual parts like cylindrical body, spherical nose and cuboidal wings and detected its effect on the Radar Cross Section in Ansys HFSS.

      [[Report](https://drive.google.com/file/d/15-ymu5gOdu_eKXco9xbrdRg-S3RaT7V9/view)]

design:
  columns: '2'
---
