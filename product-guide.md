# Digital Sovereignty for Managed Services — Product Guide
        Internal reference for AMS Customer Success Engineers. Covers Prime vs. Ultimate features, SKU details, pricing, prospecting, implementation guidance, and FAQ.

        **INTERNAL — Adobe Confidential**

      
    
  

  ## The Offering at a Glance
  Digital Sovereignty for AEM Managed Services delivers exceptional digital experiences with sovereign cloud architectures designed for jurisdictional control, security, and compliance. There are three core value propositions for CSEs to lead with:

  
    
      
        ### Accelerated Deployment with Global Reach
        Deploy in as little as a week, with automated tooling, and reduce complexity compared to on-premise or custom builds. With support across dozens of sovereign regions, gain the flexibility to meet jurisdictional requirements without sacrificing scale or performance.

      
    
    
      
        ### Comprehensive Compliance and Security Assurance
        Adopt our sovereign architecture, cleared personnel, and robust compliance for standards like FedRAMP+ and Protected C. Continuous monitoring, enhanced container security, and extended detection and response ensure sensitive data remains secure and auditable.

      
    
    
      
        ### Tailored Sovereignty for Evolving Regulations
        Adapt to new sovereign mandates with compliance customization. This flexibility, together with localized personnel and high-side deployment options, empowers governments and regulated industries to maintain operational control while delivering digital experiences.

      
    
  

  ## Security Add-ons Portfolio
  Digital Sovereignty builds on the existing AMS security add-on stack. Each tier is inclusive of the prior:

  
    
      
        ### WAF-DDoS
        25+ AMS customers. Web Application Firewall with DDoS protection. Large base to sell into.

      
    
    
      
        ### Enhanced Security (FedRAMP)
        12+ AMS customers. Includes WAF-DDoS plus FedRAMP-aligned controls.

      
    
    
      
        ### Digital Sovereignty Prime
        New. Includes WAF-DDoS + Enhanced Security + Prime sovereign features.

      
    
    
      
        ### Digital Sovereignty Ultimate
        New. Includes all Prime features plus TS-SCI clearances, compliance customization, and personnel localization.

      
    
  

  ## Prime vs. Ultimate — Feature Comparison
  All features below apply to both Prime and Ultimate unless noted. Ultimate adds the features in the bottom section.

  
    
      
        ### Feature
      
      
        ### Prime
      
      
        ### Ultimate
      
    
    
      Data sovereignty for country or region
      ✅
      ✅
    
    
      Rapid deployment
      ✅
      ✅
    
    
      Extensive cloud regions (AWS, Azure, GCP)
      ✅
      ✅
    
    
      Enhanced container security
      ✅
      ✅
    
    
      Governance and auditing (logs, SIEM)
      ✅
      ✅
    
    
      Identity and access management (IAM)
      ✅
      ✅
    
    
      Named and known personnel
      ✅
      ✅
    
    
      Extended detection and response
      ✅
      ✅
    
    
      Threat intelligence
      ✅
      ✅
    
    
      Secret-level security clearances
      ✅
      ✅
    
    
      Top Secret (TS-SCI) security clearances
      —
      ✅
    
    
      High-side deployment
      —
      ✅
    
    
      High security classifications (FedRAMP+, Protected C)
      —
      ✅
    
    
      Localization of all personnel
      —
      ✅
    
    
      Compliance customization
      —
      ✅
    
  

  ## Availability and Pricing

  
    
      
        ### Digital Sovereignty Prime
        **SKU:** 38060745

        **Available:** Now

        **What it includes:** Named and known personnel, security clearances (Secret, etc.), global threat intelligence sharing, identity & access management

        **Uplift applies to:** All AMS SKUs

        **List price:** 50% uplift on all AMS base SKUs

      
    
    
      
        ### Digital Sovereignty Ultimate
        **SKU:** 38060746

        **Available:** Now

        **What it includes:** All Prime features, plus Top Secret (TS-SCI) clearances, compliance customization (e.g. ATO Concierge), and localization of all personnel

        **Uplift applies to:** All AMS SKUs

        **List price:** 75% uplift on all AMS base SKUs

      
    
  

  ### Important Pricing Rules
  
    - Uplift is calculated on all AMS Enterprise SKUs (Sites, Assets, Forms 99.5, 99.5 HR, etc.)
    - Ultimate is inclusive of all Prime features
    - **The uplift CANNOT be discounted.** Any discount must occur on the underlying instances only.
    - Must be an add-on to AMS Enterprise
    - What customers get: Credits for CSE to apply Digital Sovereignty to environments and programs
  

  ## Implementation Guide for CSEs
  As the assigned CSE, you will manage setup and configuration of Digital Sovereignty in-region. Key points:

  
    
      
        ### Network Architecture
        
          - End-user traffic can route via customer's own CDN and Managed Gateway to the publish tier over a completely private network link
          - Authoring users access via private network link, mapped to an IP on the customer network
          - Customer can bring their own CDN/WAF, or purchase Managed CDN/WAF from Adobe
        
      
    
    
      
        ### Logging & Security Integration
        
          - Logs and telemetry can be filtered, transformed, redacted, and routed to customer SIEM
          - SSH access via integrated bastion/jump host, integrated with customer IDP
          - Customer Threat Intelligence feeds can be integrated into AMS security tooling for real-time threat sharing
        
      
    
  

  ## FAQ

  
    
      
        ### How do I know if a customer truly needs sovereignty instead of Enhanced Security?
        If they mention: (1) keeping all data in-country or in-region, (2) localized or cleared personnel only, (3) strict audit and governance obligations, (4) high-side or air-gapped environments — sovereignty is a strong fit. If they only want stronger encryption, WAF/DDoS, or key management, Enhanced Security may be sufficient.

      
    
    
      
        ### Which industries or customers are the best fit?
        Public sector and highly regulated industries are the primary targets: government agencies, healthcare, financial services, defense, and critical infrastructure. Multinationals operating across multiple jurisdictions are also key — unmanaged sovereign risk can lead to fines, brand damage, or revenue loss.

      
    
  

  
    
      
        ### Can customers still integrate with other services?
        Yes. Customers can connect to AWS or Azure services, bring their own CDN/WAF, and integrate with third-party systems. The sovereign layer ensures those integrations don't compromise compliance or data residency.

      
    
    
      
        ### Which regulations does Digital Sovereignty support?
        It supports a wide range of global frameworks including GDPR (EU), FedRAMP+ (US), Protected C (Canada), IRAP (Australia), MLPS 2.0 (China), and ISMAP (Japan). Adobe also provides compliance customization to adapt to new or local regulations not yet covered.

      
    
  

  
    
      
        ### How are security, audit, and operations handled?
        Digital Sovereignty includes independent infrastructure, single-tenant isolation, enhanced logging/telemetry, and SIEM integration. Operations may require local or cleared personnel, with support for Secret and TS-SCI clearances in some deployments. Customers get full visibility and control.

      
    
    
      
        ### What makes Adobe's sovereign offering unique?
        Unlike generic sovereign clouds, Adobe combines a best-in-class DXP with sovereign deployment models. Customers get great digital experiences and compliance. Adobe leverages AWS and Azure sovereign regions but layers on governance, auditing, cleared personnel, and compliance customization that no cloud-only vendor can match.