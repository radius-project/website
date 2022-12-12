---
####################### Banner #########################
banner:
  title : "Cloud-native applications<br />are more than just Kubernetes"
  image : "images/banner-art.svg"
  content : "Kubernetes is great, but cloud-native applications are so much more. You deserve tooling and experiences that can describe, deploy, and manage your entire app, across any cloud and any platform."
  button:
    enable : true
    label : "Demo a Radius application"
    link : "https://demo.radapp.dev"

##################### Feature ##########################
feature:
  enable : true
  title : "What Project Radius offers application teams"
  feature_item:
    # feature item loop
    - name : "App-centric Experiences"
      icon : "fas fa-window-maximize"
      content : "Developers can focus on their applications instead of underlying platform infrastructure"
      
    # feature item loop
    - name : "Abstracted Runtimes"
      icon : "fas fa-layer-group"
      content : "Developers don't need to learn Kubernetes. Instead they describe their app's requirements"

    # feature item loop
    - name : "Separation of Concerns"
      icon : "fas fa-people-arrows"
      content : "Developers focus on their apps while operators focus on environments and infrastructure"
      
    # feature item loop
    - name : "App Portability"
      icon : "fas fa-share-from-square"
      content : "Deploy your application across clouds and on-premises with zero app rewrites"
      
    # feature item loop
    - name : "Consistent Tooling"
      icon : "fas fa-screwdriver-wrench"
      content : "Developers and operators can deploy, manage, and visualize applications with common tools"
      
    # feature item loop
    - name : "Automated & Secure"
      icon : "fas fa-file-shield"
      content : "Operators can define and enforce organization best practices across applications"

######################### Service #####################
service:
  enable : true
  service_item:
    # Tooling
    - title : "Accelerate your<br />application teams"
      video:
        enable: true
        url: "https://microsoft.sharepoint.com/teams/radius/_layouts/15/embed.aspx?uniqueID=13a468f0-85a9-44a6-8113-17e4bae571b5"
      content : "We believe that developers and IT teams need better tools to work with each other. We want to help IT teams ensure all of their applications meet operational requirements for excellence and security. We also want developers to know that their applications are meeting those requirements without those developers having to be experts in those requirements."
    
    # Portable
    - title : "Build apps that are portable across clouds and on-prem"
      images:
      - "images/platforms.png"
      content : "Project Radius makes it easy to build and operate applications on Azure, AWS, and on-premises with pluggable infrastructure. Developers describe their application's requirements (_databases, caching, identity, and more_), and operators bind apps to platforms leveraging Radius environments."
      button:
        enable : true
        label : "Learn more"
        link : "https://docs.radapp.dev/administrator-guides/platforms"

    # Recipes
    - title : "Automate infrastructure<br />provisioning with Recipes"
      images:
      - "images/recipes.png"
      content : "Create reusable templates for infrastructure deployment and configuration that empower developers to quickly build applications that comply with operational and security guidelines. No more manual ticketing systems or wikis telling developers how to deploy infrastructure."
      button:
        enable : true
        label : "Check it out"
        link : "https://docs.radapp.dev/author-apps/recipes"
        
    # service item loop
    - title : "Built-in Dapr support"
      images:
      - "images/dapr-buildingblocks.png"
      content : "Developers can leverage built-in support for [Dapr building blocks](https://dapr.io) to model and deploy state stores, pub/sub brokers, and more. Simply add a building block and Radius takes care of the rest, including generating all of your Dapr component and advanced scoping and security configuration"
      button:
        enable : true
        label : "Learn More"
        link : "https://docs.radapp.dev/author-apps/dapr"
        
################### Screenshot ########################
screenshot:
  enable : false
  title : "Experience the best <br> workflow with us"
  image : "images/screenshot.svg"

  

##################### Call to action #####################
call_to_action:
  enable : true
  title : "Ready to get started?"
  image : "images/tools.png"
  content : "Visit the Project Radius getting started guide to learn more and begin rad-ifying your first application today"
  button:
    enable : true
    label : "Get Started"
    link : "https://docs.radapp.dev/getting-started"
---
