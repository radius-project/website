---
####################### Banner #########################
banner:
  title : "Developer and Operator Collaboration "
  image : "images/app-blocks.gif"
  content : "Radius is a cloud-native application platform that enables developers and the operators / platform engineers that support them to collaborate on delivering and managing cloud-native applications that follow corporate best practices for cost, operations and security, by default."
  button:
    enable : false
    label : "Learn More"
    link : "https://radapp.io/concepts/"

##################### Feature ##########################
feature:
  enable : false
  title : "What Radius offers application teams"
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
    #  Environments and Recipes
    - title : "Environments and Recipes"
      images:
      - "images/recipes.png"
      content : "Radius ensures the cloud infrastructure used by applications meets cost, operations, and security requirements. These requirements are captured in recipes, which are tied to the environment where a given application will be deployed and managed.  Environments and Recipes are defined by the IT operators, platform engineers, and/or security engineers that support cloud native developers."
     
    # Application Graph
    - title : "Application Graph"
      images:
      - "images/platforms.png"
      content : "Radius binds an application to its dependent infrastructure, which enables Radius to provide (construct?) an application graph that shows precisely how the application and infrastructure are interconnected.  This graph enables team members to view and intuitively understand what makes up an application."

    # Cloud neutral
    - title : "Cloud neutral"
      content : "Many enterprises are multi-cloud and want solutions that work well not on just Azure, but on other clouds, as well as on-premises.  So, Radius is open-source and multi-cloud from the start. With Radius, you can deploy across development environments, on-premises infrastructure and your public clouds of choice, with a single, consistent tooling experience."

    # Meet Customers where they are
    - title : "Meet Customers where they are"
      images:
      - ""
      content : "Radius meets application teams where they are by supporting proven technologies like Kubernetes, existing infrastructure tools including Terraform and Bicep and by integrating with existing CI/CD systems like GitHub Actions. Radius supports multi-tier web-plus-data to complex microservice applications like eShop, a popular cloud reference application from Microsoft."
        
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
  content : "Visit the Radius getting started guide to learn more and begin rad-ifying your first application today."
  button:
    enable : true
    label : "Get Started"
    link : "https://docs.radapp.io/getting-started"
---