---
layout: "salesforceiq-salesforce-sales-cloud-migration"
title: Migrate to Salesforce Sales Cloud from Salesforce IQ
---

<html>
<head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <title>Migrate to Salesforce Sales Cloud from Salesforce IQ - Consultant</title>
    <meta name="viewport" content="width=device-width" />
    <meta name="description" content="Are you in the process of migrating Salesforce IQ Salesforce Enterprise edition? We work alongside companies helping them set up their Salesforce instance customized to suit their business processes." />
    <meta name="keywords" content="SalesforceIQ, migrate, setup, salesforce" />
    <meta name="author" content="Allen Tom" />
    <link rel="canonical" href="https://allentom.me/salesforce-iq-salescloud-migration/" />
    <link rel="alternate" type="application/rss+xml" title="RSS" href="/feed.xml" />

    <!-- Custom CSS & Bootstrap Core CSS - Uses Bootswatch Flatly Theme: http://bootswatch.com/flatly/ -->
    <link rel="stylesheet" href="/style.css" />

    <!-- Custom Fonts -->
    <link rel="stylesheet" href="/css/font-awesome/css/font-awesome.min.css" />
    <link href="//fonts.googleapis.com/css?family=Montserrat:400,700" rel="stylesheet" type="text/css" />
    <link href="//fonts.googleapis.com/css?family=Lato:400,700,400italic,700italic" rel="stylesheet" type="text/css" />

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
    
    <!-- HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
        <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
        <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->
</head>

  <body id="page-top">

 
 
    <!-- Header -->
    <header class="masthead bg-primary text-white text-center">
      <div class="container">
        <img class="img-fluid mb-5 d-block mx-auto" src="img/profile.png" alt="">
        <h1 class="text-uppercase mb-0">Start Bootstrap</h1>
        <hr class="star-light">
        <h2 class="font-weight-light mb-0">Web Developer - Graphic Artist - User Experience Designer</h2>
      </div>
    </header>
    
<section id="features">
      <div class="container">
      <!--
        <h2 class="text-center text-uppercase">About</h2>
        <hr class="star-light">
      !-->
        <div class="row" style="margin-bottom: 3em;">
          <h3 class="text-center text-uppercase">Respond Quickly to Prospects</h3>
          <div class="col-lg-4 ml-auto">
            <p class="lead">IMAGE</p>
          </div>
          <div class="col-lg-4 mr-auto">
            <p class="lead">We setup workflow to capture lead info form your website and save it in a lead record and setting up tasks for your Sales team to reach out.</p>
          </div>
        </div>

        <div class="row" style="margin-bottom: 3em;">
          <h3 class="text-center text-uppercase">Stay on Top our Your Metrics</h3>           
          <div class="col-lg-4 ml-auto">
            <p class="lead">IMAGE</p>
          </div>
          <div class="col-lg-4 mr-auto">
            <p class="lead">We setup dashboards and reports so the team has access to the most relevant info to make really quick decisions.</p>
          </div>
        </div>

        <div class="row" style="margin-bottom: 3em;">
          <h3 class="text-center text-uppercase">Respond Quickly to Prospects</h3>            
          <div class="col-lg-4 ml-auto">
            <p class="lead">In addition to handholding you through the main feature. We help you learn advanced drag and drop features to create reports and powerful automations in a few clicks.</p>
          </div>
          <div class="col-lg-4 mr-auto">
            <p class="lead">IMAGE</p>
          </div>
        </div>

      </div>
    </section>
 

    
    
    
    
    <!-- Contact Section -->
    <section id="contact" class="bg-primary">
      <div class="container">
        <h2 class="text-center text-uppercase text-secondary mb-0">Get In Touch</h2>
        <hr class="star-dark mb-5">
        <div class="row">
          <div class="col-lg-8 mx-auto">
            <!-- To configure the contact form email address, go to mail/contact_me.php and update the email address in the PHP file on line 19. -->
            <!-- The form should work on most web servers, but if the form is not working you may need to configure your web server differently. -->
            <form action="https://webto.salesforce.com/servlet/servlet.WebToLead?encoding=UTF-8" method="POST">
                                <input type="hidden" name="oid" value="00D28000001EPHY">
                                <input type="hidden" name="retURL" value="https://allentom.me/salesforce-iq-salescloud-migration/">
                          <input type="hidden" name="lead_source" value="SalesforceIQ Migration">
                                
              <div class="control-group">
                <div class="form-group floating-label-form-group controls mb-0 pb-2">
                  <label>Name</label>
                  <input class="form-control" id="name"  name="last_name" type="text" placeholder="Name" required="required" data-validation-required-message="Please enter your name.">
                  <p class="help-block text-danger"></p>
                </div>
              </div>
              <div class="control-group">
                <div class="form-group floating-label-form-group controls mb-0 pb-2">
                  <label>Email Address</label>
                  <input class="form-control" id="email" name="email" type="email" placeholder="Email Address" required="required" data-validation-required-message="Please enter your email address.">
                  <p class="help-block text-danger"></p>
                </div>
              </div>
              <div class="control-group">
                <div class="form-group floating-label-form-group controls mb-0 pb-2">
                  <label>Phone Number</label>
                  <input class="form-control" name="phone" id="phone" type="tel" placeholder="Phone Number" required="required" data-validation-required-message="Please enter your phone number.">
                  <p class="help-block text-danger"></p>
                </div>
              </div>
              
              <div class="control-group">
                <div class="form-group floating-label-form-group controls mb-0 pb-2">
                  <label>Company Name</label>
                  <input class="form-control" name="company" id="company" type="text" placeholder="Company Name" required="required" >
                  <p class="help-block text-danger"></p>
                </div>
              </div>
              <!--
              <div class="control-group">
                <div class="form-group floating-label-form-group controls mb-0 pb-2">
                  <label>Message</label>
                  <textarea class="form-control" name="description" id="message" rows="5" placeholder="Message" required="required" data-validation-required-message="Please enter a message."></textarea>
                  <p class="help-block text-danger"></p>
                </div>
              </div>
              !-->
              <br>
              <div id="success"></div>
              <div class="form-group">
                <button type="submit" class="btn btn-primary btn-xl" id="sendMessageButton">Book Consultation</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
<!--
<div class="panel-group" id="accordion">
  <div class="panel panel-default">
    <div class="panel-heading">
      <h4 class="panel-title">
        <a data-toggle="collapse" data-parent="#accordion" href="#collapse1">
        Collapsible Group 1</a>
      </h4>
    </div>
    <div id="collapse1" class="panel-collapse collapse in">
      <div class="panel-body">Lorem ipsum dolor sit amet, consectetur adipisicing elit,
      sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
      minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
      commodo consequat.</div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading">
      <h4 class="panel-title">
        <a data-toggle="collapse" data-parent="#accordion" href="#collapse2">
        Collapsible Group 2</a>
      </h4>
    </div>
    <div id="collapse2" class="panel-collapse collapse">
      <div class="panel-body">Lorem ipsum dolor sit amet, consectetur adipisicing elit,
      sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
      minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
      commodo consequat.</div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading">
      <h4 class="panel-title">
        <a data-toggle="collapse" data-parent="#accordion" href="#collapse3">
        Collapsible Group 3</a>
      </h4>
    </div>
    <div id="collapse3" class="panel-collapse collapse">
      <div class="panel-body">Lorem ipsum dolor sit amet, consectetur adipisicing elit,
      sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
      minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
      commodo consequat.</div>
    </div>
  </div>
</div>
!-->
