---
####################### Banner #########################
banner:
  title: "Cloud-native applications<br />are more than just Kubernetes"
  image: "images/app-blocks.gif"
  content: "Radius is an open-source, cloud-native, application platform that enables developers and the operators that support them to define, deploy, and collaborate on cloud-native applications across public clouds and private infrastructure"
  button:
    enable: false
    label: "Learn More"
    link: "https://radapp.io/concepts/"

##################### Feature ##########################
feature:
  enable: false
  title: "What Radius offers application teams"
  feature_item:
    # feature item loop
    - name: "App-centric Experiences"
      icon: "fas fa-window-maximize"
      content: "Developers can focus on their applications instead of underlying platform infrastructure"
      
    # feature item loop
    - name: "Abstracted Runtimes"
      icon: "fas fa-layer-group"
      content: "Developers don't need to learn Kubernetes. Instead they describe their app's requirements"

    # feature item loop
    - name: "Separation of Concerns"
      icon: "fas fa-people-arrows"
      content: "Developers focus on their apps while operators focus on environments and infrastructure"
      
    # feature item loop
    - name: "App Portability"
      icon: "fas fa-share-from-square"
      content: "Deploy your application across clouds and on-premises with zero app rewrites"
      
    # feature item loop
    - name: "Consistent Tooling"
      icon: "fas fa-screwdriver-wrench"
      content: "Developers and operators can deploy, manage, and visualize applications with common tools"
      
    # feature item loop
    - name: "Automated & Secure"
      icon: "fas fa-file-shield"
      content: "Operators can define and enforce organization best practices across applications"

######################### Service #####################
service:
  enable: true
  service_item:
    # Developer + Operator Collaboration
    - title: "Developer + Operator Collaboration"
      images:
      - "images/collaboration.png"
      content: "Developers define Applications and their dependencies, not the underlying infrastructure. Operators define Environments with platform configuration, infrastructure, and policies that enforce their organization's requirements. Radius brings them together, deploying applications and infrastructure that meet both developer and operator requirements."
      button:
        enable: false
        label: "Learn More"
        link: "https://docs.radapp.io/concepts/application-graph"

    # Application Graph
    - title: "Application Graph"
      images:
      - "images/connections.png"
      content: "Graphs are better than lists. Instead of managing endless lists of infrastructure and resources, Radius Applications capture the relationships and dependencies within an app. This graph can be used to both deploy and understand the application."
      button:
        enable: false
        label: "Learn More"
        link: "https://docs.radapp.io/concepts/application-graph"
      
    #  Environments and Recipes
    - title: "Infrastructure Recipes"
      images:
      - "images/recipes.png"
      content: "Developers shouldn't need to be infrastructure experts. Recipes allow IT operators to define infrastructure-as-code templates used to deploy an application's infrastructure, while guaranteeing it meets cost, operations, and security requirements. Developers just focus on application requirements, not the underlying infrastructure."
      button:
        enable: true
        label: "Learn More"
        link: "https://docs.radapp.io/guides/recipes/overview"

    # Cloud neutral
    - title: "Cloud Neutral"
      images:
      - "images/platforms.png"
      content: "Teams want tools and solutions that don't lock them into a specific cloud or platform. Radius is open-source and multi-cloud from the start. With Radius, you can deploy across development environments, on-premises infrastructure, and your public clouds of choice, with a single, consistent tooling experience."

    # Meet Customers where they are
    - title: "Leverage Existing Tools"
      images:
      - "images/tooling.png"
      content: "Radius meets application teams where they are by supporting proven technologies like Kubernetes, existing infrastructure tools including Terraform and Bicep, and by integrating with existing CI/CD systems like GitHub Actions and Azure DevOps Pipelines."
        
################### Screenshot ########################
screenshot:
  enable: false
  title: "Experience the best <br> workflow with us"
  image: "images/screenshot.svg"

##################### Call to action #####################
call_to_action:
  enable: true
  title: "Ready to get started?"
  image: "images/tools.png"
  content: "Visit the Radius getting started guide to learn more and begin rad-ifying your first application today."
  button:
    enable: true
    label: "Get Started"
    link: "https://docs.radapp.io/getting-started/"
---