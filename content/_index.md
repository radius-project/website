---
####################### Banner #########################
banner:
  title : "Cloud-native applications<br />are more than just Kubernetes"
  image : "images/banner-art.svg"
  content : "Kubernetes is great, but cloud-native applications are so much more.<br />You deserve a platform that can describe, deploy, and manage your entire app."
  button:
    enable : false
    label : "Learn More"
    link : "https://radapp.dev/concepts/overview/"

##################### Feature ##########################
feature:
  enable : false
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
    #  App Graph
    - title : "Leverage the Radius<br />application graph"
      images:
      - "images/connections.png"
      content : "Applications are more than just flat lists of services; they are an interconnected graph of services, databases, gateways, and more. Project Radius allows teams to model, visualize, and automate applications through the new Radius application graph."
      button:
        enable : true
        label : "Learn more"
        link : "https://docs.radapp.dev/concepts/appmodel-concept/"
    
    # Portable
    - title : "Build apps that are portable<br />across clouds and on-prem"
      images:
      - "images/platforms.png"
      content : "Project Radius makes it easy to build and operate applications on Azure, AWS, and on-premises with pluggable infrastructure and consistent tooling. Developers describe their application's requirements (_databases, caching, identity, and more_), and operators bind apps to platforms leveraging Radius environments."
      button:
        enable : true
        label : "Learn more"
        link : "https://docs.radapp.dev/operations/platforms"

    # Tooling
    - title : "Ensure your apps meet<br />your org's requirements"
      video:
        enable: true
        url: "https://microsoft.sharepoint.com/teams/radius/_layouts/15/embed.aspx?uniqueID=13a468f0-85a9-44a6-8113-17e4bae571b5"
      content : "We believe that developers and IT ops teams need better tools to work with each other. It's too hard for ops to ensure apps meet operational requirements for excellence and security. It's even harder for developers to know their apps are meeting those requirements, without having to become experts in the underlying platforms. We're here to help with a new application-focused experience with consistent tooling across all your clouds and platforms."

    # Recipes
    #- title : "Automate infrastructure<br />provisioning with Recipes"
    #  images:
    #  - "images/recipes.png"
    #  content : "Create reusable templates for infrastructure deployment and configuration that empower #developers to quickly build applications that comply with operational and security guidelines. No more #manual ticketing systems or wikis telling developers how to deploy infrastructure."
    #  button:
    #    enable : true
    #    label : "Check it out"
    #    link : "https://docs.radapp.dev/author-apps/recipes"
        
    # service item loop
    - title : "Built-in Dapr support"
      images:
      - "images/dapr-buildingblocks.png"
      content : "Developers can leverage built-in support for [Dapr building blocks](https://dapr.io) such as state stores, pub/sub brokers, and more. When deployed, Radius binds the building blocks to supported infrastructure such as Azure Service Bus or AWS SQS, which operators can select and configure. All of your Dapr component configs and advanced security configuration is deployed and managed for you automatically."
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
  content : "Visit the Project Radius getting started guide to learn more and begin rad-ifying your first application today."
  button:
    enable : true
    label : "Get Started"
    link : "https://docs.radapp.dev/getting-started"
---
