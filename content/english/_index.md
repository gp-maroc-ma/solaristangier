---
########################### hero slider ############################
hero_slider:
  enable : true
  slider_item:
    # slider item
    - subtitle : "Solaris"
      title : "Leading Solar Module <br>Manufacturer"
      content : "Powering the future from Morocco's premier free trade zone - delivering world-class solar panels 
      to markets across Africa, Europe, and North America."
      bg_image_webp : "images/slider/_DSC0410.jpg"
      bg_image : "images/slider/_DSC0410.jpg"
      animation : "fadeInUp" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "project/"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/
        
    # slider item
    - subtitle : "Solaris"
      title : "Cutting-Edge <br>Solar Technology"
      content : "Delivering high-efficiency photovoltaic solutions to drive the global transition to sustainable energy."
      bg_image_webp : "images/slider/_DSC0584.jpg"
      bg_image : "images/slider/_DSC0584.jpg"
      animation : "fadeInLeft" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "project/"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/
        
    # slider item
    - subtitle : "Solaris"
      title : "Ethically Sourced <br>Solar Solutions"
      content : "High-efficiency panels with full traceability, meeting international quality standards and ethical 
      sourcing requirements for global markets."
      bg_image_webp : "images/slider/_DSC0631.jpg"
      bg_image : "images/slider/_DSC0631.jpg"
      animation : "fadeInRight" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "project/"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/

################################## banner feature ############################
banner_feature:
  enable : true
  # Max use 4 item
  feature_item:
    # banner feature item loop
    - name : "Innovation"
      icon : "fas fa-lightbulb" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Exploring cutting-edge technologies like TOPCon and HJT for maximum efficiency & reliability."
      
    # banner feature item loop
    - name : "Sustainability"
      icon : "fas fa-leaf" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Protecting the planet through reduced carbon footprints and renewable energy solutions."
      
    # banner feature item loop
    - name : "Quality"
      icon : "fas fa-award" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Superior products meeting international standards, verified by third-party audits & lab testing."
      
    # banner feature item loop
    - name : "Integrity"
      icon : "fas fa-handshake" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Building trust through transparency and ethical practices for long-term partnerships."


################################## about ####################################
about:
  enable : true
  subtitle : "About Us"
  title : "Company History"
  
  content : "Our first manufacturing plant was established in 2018 in Al Hoceima, becoming the first 250 MW solar panel plant in
Morocco & the largest in Africa. Founded under the parent company GPM Holding’s umbrella, the company initially focused
on supplying Solaris’ modules for solar farms throughout Morocco. In 2024, the company launched a new 750 MW facility in
a free trade zone, taking advantage of tax & tariff exemptions to optimize costs for serving international clients,
Since its inception, Solaris Tangier has maintained its position as Africa’s largest PV solar module manufacturer."
  
  bg_image : "images/backgrounds/about-us-bg.png"
  bg_image_webp : "images/backgrounds/about-us-bg.webp"
  image_webp : "images/about/57_ECOPACKR_26.jpg"
  image : "images/about/57_ECOPACKR_26.jpg"
  button:
    enable : true;
    label : "more services"
    link : "#contacts"

################################## funfacts ###############################
funfacts :
  enable : true
  funfacts_item :
    # fanfacts item loop
    - name : "Annual Capacity <br>(MW)"
      count : "750"
      icon : "fas fa-solar-panel" # font-awesome 5 : https://fontawesome.com/icons/
      
    # fanfacts item loop
    - name : "Facility Size <br>(sqm)"
      count : "10000"
      icon : "fas fa-industry" # font-awesome 5 : https://fontawesome.com/icons/
      
    # fanfacts item loop
    - name : "Performance <br>Warranty (Years)"
      count : "30"
      icon : "fas fa-shield-alt" # font-awesome 5 : https://fontawesome.com/icons/
      
    # fanfacts item loop
    - name : "Years <br>Experience"
      count : "8"
      icon : "far fa-calendar-alt" # font-awesome 5 : https://fontawesome.com/icons/


################################# feature ############################################
feature:
  enable : true
  subtitle : "Mission & Vision"
  title : "Solaris Tangier Values"
  image_webp : "images/about/_DSC0576.jpg"
  image : "images/about/_DSC0576.jpg"
  content : ""
  feature_item:
    # feature item loop
    - name : "Mission"
      icon : "fas fa-crosshairs" # font-awesome 5 : https://fontawesome.com/icons/
      content : "At Solaris Tangier, our mission is to drive the global transition to sustainable energy by delivering 
      cutting-edge, high-efficiency photovoltaic solar solutions. We are committed to advancing the quality & 
      affordability of solar technology by maintaining flexibility in our product design & modular manufacturing 
      processes in our state-of-the-art facility. Our aim is to ensure energy independence for our clients & promote 
      environmental responsibility."
      
    # feature item loop
    - name : "Vision"
      icon : "fas fa-eye" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Solaris Tangier envisions becoming Africa’s leading hub for solar panel manufacturing, supporting 
      Morocco’s renewable energy goals and reducing international reliance on China-centric supply chains. We aim to 
      deliver ethically sourced, high-efficiency solar solutions that meet the needs of both African & North American 
      markets, driving sustainable energy worldwide."
      
      
################################# service ############################################
service:
  enable : false
  subtitle : "Project Solutions"
  title : "Service We Provide"
  service_item:
    # service item loop
    - name : "GreenPower Morocco 1"
      link : "service/gpm-1/"
      logo : "images/service/logo-gpm-1.png"
      image : "images/service/image3.jpeg"
      content : "GPM Holding, through its subsidiary GreenPower Morocco 1 S.A., has successfully developed a 30 MWac 
      photovoltaic park. The facility is located at Douar Daidaat, within the Hjar Ennhal commune of the Tangier-Asilah 
      prefecture.
      <br><br>      
      Developed within the framework of Law 13-09 regarding renewable energies, the project represents a significant 
      contribution to Morocco's green energy infrastructure."
      
    # service item loop
    - name : "GreenPower Morocco 2"
      link : "service/gpm-2/"
      logo : "images/service/logo-gpm-2.png"
      image : "images/service/image6.jpeg"
      content : "GPM Holding is currently developing two additional photovoltaic solar parks: GreenPower Morocco 2 and 
      GreenPower Morocco 4.
      <br><br> 
      Like their predecessor, these projects fall under the framework of Law 13-09, which governs electricity 
      production from renewable sources and promotes the development of green energy projects in Morocco.
      <br><br> 
      GPM Holding is currently developing two additional photovoltaic solar parks: GreenPower Morocco 2 and GreenPower 
      Morocco"
      
    # service item loop
    - name : "GreenPower Morocco 4"
      link : "service/gpm-4/"
      logo : "images/service/logo-gpm-4.png"
      image : "images/service/image7.jpg"
      content : "GPM Holding is currently developing two additional photovoltaic solar parks: GreenPower Morocco 2 and 
      GreenPower Morocco 4.
      <br><br> 
      Like their predecessor, these projects fall under the framework of Law 13-09, which governs electricity 
      production from renewable sources and promotes the development of green energy projects in Morocco.
      <br><br> 
      GPM Holding is currently developing two additional photovoltaic solar parks: GreenPower Morocco 2 and GreenPower 
      Morocco"


################################# team ##############################################
team:
  enable : false
  section: "team"
  show_item : 3
  # team member comes from "content/*/team" folder

################################# project ############################################
project:
  enable : true
  section: "project"
  show_item : 3
  button:
    enable : true
    label : "more details"
    link : "project/"
  # project item comes from "content/*/project" folder

################################# blog ################################################
cta:
  enable : true
  title : "Partner with Us to Power Your Next Solar Project"
  bg_image_webp : "images/backgrounds/_DSC0422.jpg"
  bg_image : "images/backgrounds/_DSC0422.jpg"
  button:
    enable : false
    label : "get a quote"
    link : "#contacts"
    
################################# testimonial #########################################
testimonial:
  enable : false
  subtitle : "Testimonials"
  title : "What Clients Are Say?"
  testimonial_item:
    # testimonial item loop
    - client_image : "images/testimonial/client-1.jpg"
      name : "Dominic Allen"
      designation : "Designer"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit sed eiusmod tempor incididunt ut labore dolore magna aliqua.enim ad minim veniam.quis nostrud exercitation ullamco laboris nis aliquip ex ea commodo consequat. duis aute irure dolor in reprehen."
      
    # testimonial item loop
    - client_image : "images/testimonial/client-2.jpg"
      name : "Alex Pitt"
      designation : "Designer"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit sed eiusmod tempor incididunt ut labore dolore magna aliqua.enim ad minim veniam.quis nostrud exercitation ullamco laboris nis aliquip ex ea commodo consequat. duis aute irure dolor in reprehen."

    # testimonial item loop
    - client_image : "images/testimonial/client-3.jpg"
      name : "John Doe"
      designation : "Designer"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit sed eiusmod tempor incididunt ut labore dolore magna aliqua.enim ad minim veniam.quis nostrud exercitation ullamco laboris nis aliquip ex ea commodo consequat. duis aute irure dolor in reprehen."

################################# partners #########################################
partners:
  enable : false
  subtitle : "PARTNERS"
  title : "Our Strategic Partners"
  partners_item:
    
      
    # partners item loop
    - partner_logo : "images/partners/partner-3.png"
      name : "The Moroccan Agency for Investment and Export Development"
      description : "[Visit site](https://amdie.gov.ma/)"    
      
    # partners item loop
    - partner_logo : "images/partners/partner-2.png"
      name : "The U.S. International Development Finance Corporation"
      description : "[Visit site](https://www.dfc.gov/)"      
    # partners item loop
    - partner_logo : "images/partners/partner-1.jpg"
      name : "Advanced Material Solutions"
      description : "[Visit site](https://silicongases.com/polysilicon)"
  
      
################################# blog ################################################
blog:
  enable : false
  section : "blog"
  show_item : 3
  # blog post comes from "content/*/blog" folder

################################# contacts ################################################
contact:
  enable : true
  image : "images/globe-2.jpg"

  form_fields:
    # form item
    - id: "name"
      label: "Name"
      type: input
      input_type: text
      placeholder: "Name *"
      name: "entry.1436542053"
      maxlength: 255
      required: true

    # form item
    - id:  "email"
      label: "Email"
      type: input
      input_type: email
      placeholder: "Email *"
      name: "emailAddress"
      pattern: '^([\w-]+(?:\.[\w-]+)*)@((?:[\w-]+\.)*\w[\w-]{0,66})\.([a-z]{2,6}(?:\.[a-z]{2})?)$'
      maxlength: 255
      required: true

    # form item
    - id:  "confirm_email"
      label: "Confirm Email"
      type: input
      input_type: email
      placeholder: "Confirm Email *"
      name: "entry.1404406591"
      pattern: '^([\w-]+(?:\.[\w-]+)*)@((?:[\w-]+\.)*\w[\w-]{0,66})\.([a-z]{2,6}(?:\.[a-z]{2})?)$'
      maxlength: 255
      required: false
      hidden: true

    # form item
    - id:  "phone"
      label: "Telephone"
      type: input
      input_type: text
      placeholder: "Telephone"
      name: "entry.1333006019"
      maxlength: 15
      required: false

    # form item
    - id:  "subject"
      label: "Subject"
      type: input
      input_type: text
      placeholder: "Subject"
      name: "entry.2008139399"
      maxlength: 255
      required: false

    # form item
    - id:  "message"
      label: "Message"
      type: textarea
      input_type: text
      placeholder: "Your Message *"
      name: "entry.1150758010"
      maxlength: 400
      required: true

    # form item
    - id : "language"
      label: "Language"
      type: select
      input_type: text
      placeholder: "Language"
      name: "entry.740536652"
      required: false
      hidden: true
      default: "EN"

---
