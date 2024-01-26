
# 📗 THE BUBBLE MANUAL



## TABLE OF CONTENTS



### INTRO

- [Introduction](#introduction)
- [New? Start Here](#new-start-here)
- [What is Bubble?](#what-is-bubble)
- [The Glossary](#the-glossary)



### USER MANUAL

+ [Getting started](#getting-started)
   - [What is Bubble?](#what-is-bubble)
   + [Building your first app](#building-your-first-app)
      - [Planning features](#planning-features)
      - [Database structure](#database-structure)
      - [Design and UX](#design-and-ux)
   - [Creating and managing apps](#creating-and-managing-apps)
   + [The Bubble editor](#the-bubble-editor)
      + [Tabs and sections](#tabs-and-sections)
         + [Design tab](#design-tab)
            - [The element tree](#the-element-tree)
            - [The property editor](#the-property-editor)
         - [Workflow tab](#workflow-tab)
         - [Data tab](#data-tab)
         - [Styles tab](#styles-tab)
         - [Plugins tab](#plugins-tab)
         + [Settings tab](#settings-tab)
            + [Application settings](#application-settings)
               - [Custom headers/body](#custom-headersbody)
               - [Visual settings](#visual-settings)
               - [Social media sharing](#social-media-sharing)
               - [Translating your app](#translating-your-app)
               - [Email settings](#email-settings)
               - [Collaboration](#collaboration)
            - [Custom domain and DNS](#custom-domain-and-dns)
         - [Logs tab](#logs-tab)
   + [Tools](#tools)
      - [Key features](#key-features)
      - [The search tool](#the-search-tool)
      - [The issue tracker](#the-issue-tracker)
      - [The element tree](#the-element-tree)
      - [The element property editor](#the-element-property-editor)
      - [The debugger](#the-debugger)
      - [Notes](#notes)
   - [Previewing your app](#previewing-your-app)
   - [Deploying your app](#deploying-your-app)
+ [Design](#design)
   + [Elements](#elements)
      + [The element hierarchy](#the-element-hierarchy)
         - [The element tree](#the-element-tree)
      - [The page](#the-page)
   + [Containers](#containers)
      - [Groups](#groups)
      - [Repeating groups](#repeating-groups)
      - [Table elements](#table-elements)
      - [Popups](#popups)
      - [Floating groups](#floating-groups)
      - [Group focus](#group-focus)
      - [Visual elements](#visual-elements)
   + [Input forms](#input-forms)
      - [Text and numbers](#text-and-numbers)
      - [Dates and time](#dates-and-time)
      - [File uploads](#file-uploads)
      - [Selection controls](#selection-controls)
      - [Reusable Elements](#reusable-elements)
   + [Styling](#styling)
      - [Color variables](#color-variables)
      - [Font variables](#font-variables)
      - [Styles](#styles)
      - [Custom Fonts](#custom-fonts)
   + [Responsive design](#responsive-design)
      - [Building responsive pages](#building-responsive-pages)
      + [Legacy articles](#legacy-articles)
         - [The Basics (Legacy)](#the-basics-legacy)
         - [Building Responsive Pages (Legacy)](#building-responsive-pages-legacy)
         - [Migrating Legacy Pages](#migrating-legacy-pages)
         - [Tips When Designing (Legacy)](#tips-when-designing-legacy)
   - [Templates](#templates)
   - [The Component Library](#the-component-library)
   - [Importing from Figma](#importing-from-figma)
+ [Data](#data)
   + [The database](#the-database)
      - [Data types and fields](#data-types-and-fields)
      - [Creating, saving and deleting data](#creating-saving-and-deleting-data)
      - [Finding data](#finding-data)
      - [Displaying data](#displaying-data)
      - [Protecting data with privacy rules](#protecting-data-with-privacy-rules)
      - [The database editor](#the-database-editor)
   + [Export/import data](#exportimport-data)
      - [Exporting data](#exporting-data)
      - [Importing data (CSV)](#importing-data-csv)
      - [Working with location data](#working-with-location-data)
      - [Using Algolia](#using-algolia)
   + [Database structure by app type](#database-structure-by-app-type)
      - [Marketplace Apps](#marketplace-apps)
      - [Directory & Listings Apps](#directory-listings-apps)
      - [Social Network Apps](#social-network-apps)
      - [SaaS Apps](#saas-apps)
      - [Project Management Apps](#project-management-apps)
      - [CRM Apps](#crm-apps)
      - [Professional Services Apps](#professional-services-apps)
      - [On-demand Apps](#on-demand-apps)
      - [Documentation/ CMS Apps](#documentation-cms-apps)
      - [Applicant Tracking System (ATS) Apps](#applicant-tracking-system-ats-apps)
      - [Portfolio Apps](#portfolio-apps)
      - [Gallery Apps](#gallery-apps)
      - [Online Store / Ecommerce Apps](#online-store-ecommerce-apps)
      - [Blog Apps](#blog-apps)
      - [Messaging App](#messaging-app)
      - [Dashboards](#dashboards)
      - [Building Block Apps](#building-block-apps)
      - [Bubble as a backend](#bubble-as-a-backend)
   - [Files](#files)
   + [Static data](#static-data)
      - [App texts (translations)](#app-texts-translations)
      - [Option sets](#option-sets)
   + [Temporary data](#temporary-data)
      - [Custom states](#custom-states)
      - [URL parameters](#url-parameters)
   + [User accounts](#user-accounts)
      + [Authentication plugins](#authentication-plugins)
         - [Facebook plugin](#facebook-plugin)
         - [Fitbit plugin](#fitbit-plugin)
         - [Google plugin](#google-plugin)
         - [Instagram plugin](#instagram-plugin)
         - [Linkedin plugin](#linkedin-plugin)
         - [Pinterest plugin](#pinterest-plugin)
         - [Slack plugin](#slack-plugin)
         - [Wistia plugin](#wistia-plugin)
         - [YouTube plugin](#youtube-plugin)
      - [Cookies set by Bubble](#cookies-set-by-bubble)
+ [Logic](#logic)
   - [The frontend and backend](#the-frontend-and-backend)
   + [Workflows](#workflows)
      + [Events](#events)
         + [Frontend events](#frontend-events)
            - [Recurring workflows](#recurring-workflows)
            - [Custom events](#custom-events)
         + [Backend events](#backend-events)
            - [Database trigger events](#database-trigger-events)
      - [Actions](#actions)
      - [API Workflows](#api-workflows)
   - [Dynamic expressions](#dynamic-expressions)
   - [Conditions](#conditions)
   + [Navigation](#navigation)
      - [Single-page applications (SPA)](#single-page-applications-spa)
      - [Multi-page applications](#multi-page-applications)
      - [Page slugs](#page-slugs)
+ [Maintenance](#maintenance)
   - [Collaborators](#collaborators)
   + [Version control](#version-control)
      - [Best practices: Version control](#best-practices-version-control)
      - [Transitioning from the legacy version control](#transitioning-from-the-legacy-version-control)
      - [Terminology: Version control](#terminology-version-control)
      - [Version Control (legacy)](#version-control-legacy)
   - [Commenting](#commenting)
   + [Database maintenance](#database-maintenance)
     - [Copying the database](#copying-the-database)
     - [Restoring database backups](#restoring-database-backups)
     - [Bulk operations](#bulk-operations)
     - [Wiping change history](#wiping-change-history)
   + [Performance](#performance)
     + [Optimizing for workload](#optimizing-for-workload)
        - [Understanding the workload calculation](#understanding-the-workload-calculation)
        - [Planning for workload](#planning-for-workload)
        - [Searches](#searches)
        - [Page load](#page-load)
        - [Workflows and actions](#workflows-and-actions)
        - [Backend workflows](#backend-workflows)
     - [Hard limits](#hard-limits)
     - [Capacity Usage (legacy)](#capacity-usage-legacy)
     - [Notes on queries](#notes-on-queries)
   + [SEO](#seo)
     - [Introduction to SEO](#introduction-to-seo)
     - [SEO: App](#seo-app)
     - [SEO: Page](#seo-page)
   + [Testing and debugging](#testing-and-debugging)
     - [Introduction to testing and debugging](#introduction-to-testing-and-debugging)
     - [The debugger](#the-debugger)
     - [The server logs](#the-server-logs)
     - [Supported browsers](#supported-browsers)
   - [API workflow scheduler](#api-workflow-scheduler)
+ [Integrations](#integrations)
   + [API](#api)
      + [Introduction to APIs](#introduction-to-apis)
         - [What is a RESTful API?](#what-is-a-restful-api)
      + [The Bubble API](#the-bubble-api)
         - [Bubble API terminology](#bubble-api-terminology)
         + [Authentication](#authentication)
            - [How to authenticate](#how-to-authenticate)
            - [No authentication](#no-authentication)
            - [As a User](#as-a-user)
            - [As an admin](#as-an-admin)
         + [The Data API](#the-data-api)
            - [Data API Privacy Rules](#data-api-privacy-rules)
            - [Data API endpoints](#data-api-endpoints)
            - [Data API requests](#data-api-requests)
         + [The Workflow API](#the-workflow-api)
            - [Workflow API Privacy Rules](#workflow-api-privacy-rules)
            - [Workflow API endpoints](#workflow-api-endpoints)
            + [API workflows](#api-workflows)
               - [Creating API workflows](#creating-api-workflows)
               - [Scheduling API workflows](#scheduling-api-workflows)
               - [Recursive API workflows](#recursive-api-workflows)
               - [API Workflow Scheduler](#api-workflow-scheduler)
               - [Case: Stripe notifications](#case-stripe-notifications)
      + [The API Connector](#the-api-connector)
         - [Authentication](#authentication)
         - [API Connector security](#api-connector-security)
         + [Case: Google Translate](#case-google-translate)
            - [How to setup Google API keys](#how-to-setup-google-api-keys)
      - [API security](#api-security)
      - [Plugins that connect to APIs](#plugins-that-connect-to-apis)
      - [API Glossary](#api-glossary)
   + [Plugins](#plugins)
      - [What Plugins Can Do](#what-plugins-can-do)
      - [Installing and using Plugins](#installing-and-using-plugins)
      - [Authentication plugins](#authentication-plugins)
      - [Special Plugins](#special-plugins)
   - [SQL Database Connector](#sql-database-connector)
   - [Bubble App Connector](#bubble-app-connector)
+ [Infrastructure](#infrastructure)
   + [Security](#security)
     + [Bubble's security features](#bubbles-security-features)
     - [Planning app security](#planning-app-security)
     - [Client-side and server-side](#client-side-and-server-side)
     - [Bubble account security](#bubble-account-security)
     - [App security](#app-security)
     - [Page security](#page-security)
     - [Database security](#database-security)
     + [API security](#api-security)
        - [API Connector security](#api-connector-security)
        - [Data API security](#data-api-security)
        - [Workflow API security](#workflow-api-security)
     - [Cookies](#cookies)
     - [Security checklist](#security-checklist)
  - [Sub-apps](#sub-apps)
  - [Bubble release tiers](#bubble-release-tiers)
  + [Hosting and scaling](#hosting-and-scaling)
     - [How Bubble hosting works](#how-bubble-hosting-works)
     - [Scaling with Bubble](#scaling-with-bubble)
     - [CDN (Cloudflare)](#cdn-cloudflare)
     - [Domain and DNS](#domain-and-dns)
     - [Bubble app names](#bubble-app-names)
  + [Compliance](#compliance)
     - [GDPR](#gdpr)
     - [SOC 2 Type II](#soc-2-type-ii)
     - [HIPAA](#hipaa)
     - [Other frameworks and standards](#other-frameworks-and-standards)
+ [Bubble for Enterprise](#bubble-for-enterprise)
   + [Hosting and infrastructure](#hosting-and-infrastructure)
      - [Dedicated instance](#dedicated-instance)
   + [Security and compliance](#security-and-compliance)
      - [Single sign-on (SSO)](#single-sign-on-sso)
      - [GDPR](#gdpr)
      - [SOC 2 Type II](#soc-2-type-ii)
      - [HIPAA](#hipaa)
      - [Other frameworks](#other-frameworks)
      - [Bubble's security features](#bubbles-security-features)
   - [Admin and collaboration](#admin-and-collaboration)
   - [Priority support](#priority-support)



### [CORE REFERENCE](#core-reference)

- [Using the core reference](#using-the-core-reference)
+ [Bubble's Interface](#bubbles-interface)
   - [Design tab](#design-tab)
   - [Workflow tab](#workflow-tab)
   - [Data tab](#data-tab)
   - [Styles tab](#styles-tab)
   - [Plugins tab](#plugins-tab)
   - [Settings tab](#settings-tab)
   - [Logs tab](#logs-tab)
   - [Template tab](#template-tab)
   - [Toolbar](#toolbar)
   - [Top and context menu options](#top-and-context-menu-options)
   + [Deployment and version control](#deployment-and-version-control)
      - [Deployment & Version Control Dropdown (legacy)](#deployment-version-control-dropdown-legacy)
+ [Elements](#elements)
   - [General Properties](#general-properties)
   - [General Properties (Legacy)](#general-properties-legacy)
   - [Styling Properties](#styling-properties)
   - [Styling Properties (Legacy)](#styling-properties-legacy)
   - [Responsive Properties](#responsive-properties)
   - [Responsive Properties (Legacy)](#responsive-properties-legacy)
   - [Conditional formatting](#conditional-formatting)
   - [States](#states)
   - [Page Element](#page-element)
      - [Page Element (Legacy)](#page-element-legacy)
   - [Visual Elements](#visual-elements)
   - [Containers](#containers)
   - [Container Layout Types](#container-layout-types)
   - [Containers (Legacy)](#containers-legacy)
   - [Input Forms](#input-forms)
   - [Reusable Elements](#reusable-elements)
   - [Element Templates (legacy)](#element-templates-legacy)
- [Workflows](#workflows)
+ [Events](#events)
   - [General Events](#general-events)
   - [Element Events](#element-events)
   - [Custom Events](#custom-events)
   - [Recurring Event](#recurring-event)
   - [Trigger Event](#trigger-event)
+ [Actions](#actions)
   - [Account](#account)
   - [Navigation](#navigation)
   - [Data (Things)](#data-things)
   - [Email](#email)
   - [Element](#element)
   - [Custom](#custom)
+ [Data](#data)
  - [Data Sources](#data-sources)
  - [Operators and comparisons](#operators-and-comparisons)
  - [Search](#search)
  - [Privacy](#privacy)
- [Styles](#styles)
+ [API](#api)
   + [The Bubble API](#the-bubble-api)
      + [The Data API](#the-data-api)
         - [Authentication](#authentication)
         - [Data API endpoints](#data-api-endpoints)
         - [Data API requests](#data-api-requests)
      - [The Workflow API](#the-workflow-api)
   + [The API Connector](#the-api-connector)
      - [Authentication](#authentication-1)
      - [Adding calls](#adding-calls)
+ [Bubble-made Plugins](#bubble-made-plugins)
   - [AddtoAny Share Buttons](#addtoany-share-buttons)
   - [Airtable](#airtable)
   - [API Connector](#api-connector-1)
   - [Blockspring](#blockspring)
   - [Box](#box)
   - [Braintree](#braintree)
   - [Bubble App Connector](#bubble-app-connector-1)
   - [Chart.js](#chartjs)
   - [Circle Music Player](#circle-music-player)
   - [Disqus](#disqus)
   - [DocuSign](#docusign)
   - [Draggable Elements](#draggable-elements)
   - [Dropzone](#dropzone)
   - [Facebook](#facebook)
   - [Fitbit](#fitbit)
   - [Full Calendar](#full-calendar)
   - [Google](#google)
   - [Google Analytics](#google-analytics)
   - [Google Optimize](#google-optimize)
   - [Google Places](#google-places)
   - [Ionic Elements](#ionic-elements)
   - [Ipiphy](#ipiphy)
   - [iTunes](#itunes)
   - [Slidebar Menu](#slidebar-menu)
   - [LinkedIn](#linkedin)
   - [Localize Translation](#localize-translation)
   - [Mailchimp](#mailchimp)
   - [Mixpanel](#mixpanel)
   - [Mouse & Keyboard Interactions](#mouse--keyboard-interactions)
   - [Multiselect Dropdown](#multiselect-dropdown)
   - [Olark Live Chat](#olark-live-chat)
   - [OneSignal Web Notifications](#onesignal-web-notifications)
   - [Pexels](#pexels)
   - [Progress Bar](#progress-bar)
   - [reCAPTCHA](#recaptcha)
   - [Rich Text Editor](#rich-text-editor)
   - [Rich Text Editor (Legacy)](#rich-text-editor-legacy)
   - [Screenshotlayer](#screenshotlayer)
   - [SelectPDF](#selectpdf)
   - [Slack](#slack)
   - [Segment](#segment)
   - [Slick Slideshow](#slick-slideshow)
   - [SQL Database Connector](#sql-database-connector)
   - [Star Rating](#star-rating)
   - [Stripe](#stripe)
   - [Tinder-like Element](#tinder-like-element)
   - [Twilio Video Chat](#twilio-video-chat)
   - [Twitter](#twitter)
   - [Wistia](#wistia)
   - [YouTube](#youtube)
   - [Zapier](#zapier)
   - [Ziggeo](#ziggeo)
   - [Pinterest](#pinterest)
 - [Application Settings](#application-settings)
    - [App plan](#app-plan)
    - [General](#general)
    - [Domain / email](#domain--email)
    - [Languages](#languages)
    - [SEO / metatags](#seo--metatags)
    - [API](#api-1)
    - [Collaboration](#collaboration)
    - [Sub-apps](#sub-apps)
    - [Versions](#versions)



### [ACCOUNT & MARKETPLACE](#account--marketplace)

+ [Account & Billing](#account--billing)
   + [Pricing and workload](#pricing-and-workload)
      - [What contributes to workload?](#what-contributes-to-workload)
      - [Using App Metrics](#using-app-metrics)
      - [Plans and billing](#plans-and-billing)
      - [Billing cycle](#billing-cycle)
      - [FAQ: Pricing and Workload](#faq-pricing-and-workload)
      - [Plans & Billing (legacy)](#plans--billing-legacy)
   - [Account Management](#account-management)
   - [Building Apps for Others](#building-apps-for-others)
   - [Selling on the Marketplace](#selling-on-the-marketplace)
+ [Official Bubble Certification](#official-bubble-certification)
   - [Hiring certified developers](#hiring-certified-developers)
+ [Building Plugins](#building-plugins)
   - [The Plugin Editor](#the-plugin-editor)
   - [General Settings](#general-settings)
   - [Updating to Plugin API v4](#updating-to-plugin-api-v4)
   - [Adding API Connections](#adding-api-connections)
   - [Building Elements](#building-elements)
   - [Building Actions](#building-actions)
   - [Loading Data](#loading-data)
   - [Publishing & Versioning](#publishing--versioning)
   - [Github Integration](#github-integration)
- [Building Templates](#building-templates)
- [Application and data ownership](#application-and-data-ownership)
- [Bug reports](#bug-reports)



### [PRE-RELEASE](#pre-release)

- [Dynamic expressions (beta)](#dynamic-expressions-beta)












=============================================














==================================================================













### USER MANUAL

# Getting started












---


# What is Bubble?












---


# Building your first app












---


# Planning features












---


# Database structure












---


# Design and UX












---


# Creating and managing apps












---


# The Bubble editor












---


# Tabs and sections












---


# Design tab












---


# The element tree












---


# The property editor












---


# Workflow tab












---


# Data tab












---


# Styles tab












---


# Plugins tab












---


# Settings tab












---


# Application settings












---


# Custom headers/body












---


# Visual settings












---


# Social media sharing












---


# Translating your app












---


# Email settings












---


# Collaboration












---


# Custom domain and DNS












---


# Logs tab












---


# Tools












---


# Key features












---


# The search tool












---


# The issue tracker












---


# The element tree












---


# The element property editor












---


# The debugger












---


# Notes












---


# Previewing your app












---


# Deploying your app












---


# Design












---


# Elements












---


# The element hierarchy












---


# The element tree












---


# The page












---


# Containers












---


# Groups












---


# Repeating groups












---


# Table elements












---


# Popups












---


# Floating groups












---


# Group focus












---


# Visual elements












---


# Input forms












---


# Text and numbers












---


# Dates and time












---


# File uploads












---


# Selection controls












---


# Reusable Elements












---


# Styling












---


# Color variables












---


# Font variables












---


# Styles












---


# Custom Fonts












---


# Responsive design












---


# Building responsive pages












---


# Legacy articles












---


# The Basics (Legacy)







---


# Building Responsive Pages (Legacy)







---


# Migrating Legacy Pages







---


# Tips When Designing (Legacy)







---


# Templates












---


# The Component Library












---


# Importing from Figma












---


# Data












---


# The database












---


# Data types and fields












---


# Creating, saving and deleting data












---


# Finding data












---


# Displaying data












---


# Protecting data with privacy rules












---


# The database editor












---


# Export/import data












---


# Exporting data












---


# Importing data (CSV)












---


# Working with location data












---


# Using Algolia












---


# Database structure by app type












---


# Marketplace Apps












---


# Directory & Listings Apps












---


# Social Network Apps












---


# SaaS Apps












---


# Project Management Apps












---


# CRM Apps












---


# Professional Services Apps












---


# On-demand Apps












---


# Documentation/ CMS Apps












---


# Applicant Tracking System (ATS) Apps












---


# Portfolio Apps












---


# Gallery Apps












---


# Online Store / Ecommerce Apps












---


# Blog Apps












---


# Messaging App












---


# Dashboards












---


# Building Block Apps












---


# Bubble as a backend












---


# Files












---


# Static data












---


# App texts (translations)












---


# Option sets












---


# Temporary data












---


# Custom states












---


# URL parameters












---


# User accounts












---


# Authentication plugins












---


# Facebook plugin












---


# Fitbit plugin












---


# Google plugin












---


# Instagram plugin












---


# Linkedin plugin












---


# Pinterest plugin












---


# Slack plugin












---


# Wistia plugin












---


# YouTube plugin












---


# Cookies set by Bubble












---


# Logic












---


# The frontend and backend












---


# Workflows












---


# Events












---


# Frontend events












---


# Recurring workflows












---


# Custom events












---


# Backend events












---


# Database trigger events












---


# Actions












---


# API Workflows












---


# Dynamic expressions












---


# Conditions












---


# Navigation












---


# Single-page applications (SPA)












---


# Multi-page applications












---


# Page slugs












---


# Maintenance












---


# Collaborators












---


# Version control












---


# Best practices: Version control












---


# Transitioning from the legacy version control












---


# Terminology: Version control












---


# Version Control (legacy)







---


# Commenting












---


# Database maintenance












---


# Copying the database












---


# Restoring database backups












---


# Bulk operations












---


# Wiping change history












---


# Performance












---


# Optimizing for workload












---


# Understanding the workload calculation












---


# Planning for workload












---


# Searches












---


# Page load












---


# Workflows and actions


# Workflows and Actions

In the earlier article [Understanding Workload Calculation](#), we explored the theme park entry ticket metaphor to illustrate that the activity type/cost table reflects the cost of entry, but you can still add additional workload by accessing different rides inside of the park.

This is especially true for workflows; each workflow can have a very low or even zero entry cost, but as you add dynamic expressions to it, the number and complexity of server requests can go up accordingly.

In this article, we'll continue looking at how different workflows – and the operations that you add to a workflow – contribute to the net total.

## Workflow Volume

Before we dive in, we'll repeat a point from earlier: each workflow in isolation does not usually incur a substantial workload cost. Of course, it still makes sense to optimize each and every workflow to be as efficient as it can be without compromising on UX or features, but there are also deadlines and developer resources to think about.

The way to prioritize is to look at workflows that have two similarities in common:
- They contain operations that typically consume a relatively high amount of workload, such as:
  - Database searches
  - Changing/copying/deleting a list of things
  - Scheduling bulk operations (API workflows on a list or recursive workflows)
- They are repeated frequently, such as:
  - Many times per user
  - Many times as a result of user growth

What we can learn from this is that a "heavy" operation that runs infrequently is not necessarily a big consumer of workload. Likewise, a frequent operation that is very lightweight is not necessarily worth optimizing. As you plan your workloads, try to identify those that spend a high amount over time. These are the ones that you want to try to optimize.

## The Total Calculation of an Action

Like we've done a few times in this article series, we'll have a look at how running an action is akin to the "entry ticket" metaphor.

In the example above, we want a list of Products to have a price that's an average of another list of products. Let's look at what we're doing:

1. First, we're starting the [Make changes to a list of things](#) action.
   - The total cost of the operation depends on the volume of the list and the number of changes being made.
2. Then, we perform a [Do a search for](#) to find the list of Products we want to make changes to.
3. Then, to make the requested change, we use another [Do a search for](#) and add the average operator to calculate the final price.

As we've seen in some of the earlier examples, it's important to be aware of the total work we're asking the server to do. We are not just running the Make changes to a list action, but also performing two database queries (Do a search for).

There are not necessarily any more efficient ways to do this: Make changes to a list of things is still more WU-friendly than Schedule API workflow on a list and recursive workflows. Make changes to a list of things works well for smaller lists (up to a few hundred things), but may time out if the list is too long.

The purpose is not to caution against the use of this action or its searches, but to further illustrate that WU consumption does not only depend on the specific action, but on other factors, as we listed above.

## Number of Actions

The number of server-side actions in a workflow has an impact on WU. With that in mind, when you develop your app and plan for WU consumption, it makes sense to think of each action in isolation rather than each workflow. A workflow in itself doesn't incur any cost; it's just the combination of a trigger and a collection of actions – a folder, if you will.

There are a few things you can do to reduce the number of actions running in a workflow:
- Consider each action and see if it's needed. Can one or more actions be combined into one?
- Do all actions have to be executed every time the workflow runs, or could you stop one or more of them from running by using the [Terminate this workflow](#) action?

## Working with Lists of Things

Some actions work with a list of database things, as opposed to just one thing. Although these actions can be very useful, it's worth noting that processing a list of things demands more from the server compared to handling a single item, resulting in a greater WU cost. Actions include:
- [Make changes to a list of things](#)
- [Delete a list of things](#)
- [Copy a list of things](#)

Using these actions is still less costly than using Schedule API workflow on a list or a recursive workflow. As such, it's important to note that we're not cautioning against their use – but merely pointing out that working with lists gives the server more work to do than working with a single item. Knowing that, you can make informed design and development decisions.

## Do When Condition Is True and Conditions

Do when condition is true works by checking a condition to see if it's true, and executing a workflow if it is. Do when condition is true is based on dynamic expressions, that can happen client-side or server-side, depending on what the condition is checking. Let's quickly look at a few examples.

### Checking Something in the Database (Server-side)

The database is stored and maintained securely on Bubble's servers. As such, any condition that requires communication with the database (whether it's creating, reading, updating, or deleting something) will incur a slight WU cost.

In this example, we are running a workflow if the number of users in your app exceeds 100. Note that Every time is checked, which means that every time a new user is added to your app, the condition will be re-checked, and the workflow will run.

It should be noted that this communication with the server can happen more often than you think:
- As the condition is first checked, Bubble performs a database query.
- As your database is updated (by that user or anyone else), Bubble's server may send the updated information to the user's device, again incurring a small WU cost.

Knowing this, we can again ask a few questions to optimize:
- Is the workflow needed at all?
- Does Run this - every time need to be selected, or can I reduce its frequency by instead selecting Just once?
- Is there some way we can trigger it by something other than a server-side condition? Such as a client-side condition or user action?
- The condition will usually be checked on page load. In other words, it will be checked every time a user loads a page. Can we avoid this somehow?

There are two lessons you should take away from this. The first is that the condition itself might incur a workload cost. The second is that the actions inside of that workflow may execute more often than you intended if you are not careful when setting up the Do when condition is true conditional expression.

### Checking If an Element Is Visible (Client-side)

Let's have a look at another example. In this one, we are checking if a group element is visible in order to trigger the workflow:

In this example, we are checking something on the user's device: whether a group is visible. This doesn't need Bubble's server to get involved, and does not incur a WU cost. However, it's less secure.

Bubble can verify if a condition holds true directly on the user's device, meaning the check is done client-side and doesn't involve Workload Units (WU). This kind of condition is executed swiftly as it doesn't require server communication, but it's less secure.

Employ client-side conditions for workflows where security isn't a major concern.

## The Order in a Conditional Expression

The order in which you place multiple conditions in a dynamic expression can make a difference in your WU consumption (as well as the speed at which Bubble will complete checking the condition). Before we dive into the example, let's summarize the logic with two simple rules:
- Bubble reads conditions from left to right.
- If any step connected with the and operator in the conditional expression returns a "no," Bubble will not check the rest of the conditions.

In other words, Bubble doesn't do more work than it has to when checking conditions. If a condition has two steps (connected with the and operator, as opposed to the or operator), and the first condition returns a "no," the second step will be disregarded. You can use this to your advantage. Let's combine the two conditions from our earlier example to see how this can work in practice.

In this example, the conditional expression has two steps: the first one is performed client-side, and the second one server-side.

In the example above, the condition has two steps, combined with the and operator:
- Is the element called Group example visible? and
- Is the number of users in the database more than 100?

If the first condition returns a "no," Bubble will not check the second, meaning that in that case, the condition has not incurred any WU cost. If you used the or operator, Bubble would have to check both of them, since any of them being true would return a "yes."
The example above would also be more secure than only using a client-side condition. If a user was able to somehow manipulate the first step to return a "yes" you didn't intend, the second server-side condition still cannot be tampered with and will return the correct response.

## Summary

Let's go over the points we've covered in this article:

- Workflows start with low impact but can increase in workload with added expressions and server-side actions.
- Prioritize workflows that are both high in workload and frequently executed.
- Consider overall workload, including associated database queries, not just the action itself.
- Merge actions when possible and use "Terminate this workflow" to stop unnecessary operations.
- Operations on lists are more demanding than single items. Faster and don't add to workload but offer less security.
- Bubble stops evaluating "and" conditions after a "no," which can reduce workload.
- Optimize workflows for workload without compromising security or user experience.



---


# Backend workflows












---


# Hard limits












---


# Capacity Usage (legacy)







---


# Notes on queries












---


# SEO












---


# Introduction to SEO












---


# SEO: App












---


# SEO: Page












---


# Testing and debugging












---


# Introduction to testing and debugging












---


# The debugger












---


# The server logs












---


# Supported browsers












---


# API workflow scheduler












---


# Integrations












---


# API












---


# Introduction to APIs












---


# What is a RESTful API?












---


# The Bubble API












---


# Bubble API terminology












---


# Authentication












---


# How to authenticate












---


# No authentication












---


# As a User












---


# As an admin












---


# The Data API












---


# Data API Privacy Rules












---


# Data API endpoints












---


# Data API requests












---


# The Workflow API












---


# Workflow API Privacy Rules












---


# Workflow API endpoints












---


# API workflows












---


# Creating API workflows












---


# Scheduling API workflows












---


# Recursive API workflows












---


# API Workflow Scheduler












---


# Case: Stripe notifications












---


# The API Connector












---


# Authentication












---


# Adding calls












---


# Case: Google Translate












---


# How to setup Google API keys












---


# API security












---


# Plugins that connect to APIs












---


# API Glossary












---


# Plugins












---


# What Plugins Can Do












---


# Installing and using Plugins












---


# Authentication plugins












---


# Special Plugins












---


# SQL Database Connector












---


# Bubble App Connector












---


# Infrastructure












---


# Security












---


# Bubble's security features












---


# Planning app security












---


# Client-side and server-side












---


# Bubble account security












---


# App security












---


# Page security












---


# Database security












---


# API security












---


# API Connector security












---


# Data API security












---


# Workflow API security












---


# Cookies












---


# Security checklist












---


# Sub-apps












---


# Bubble release tiers












---


# Hosting and scaling












---


# How Bubble hosting works












---


# Scaling with Bubble












---


# CDN (Cloudflare)












---


# Domain and DNS












---


# Bubble app names












---


# Compliance












---


# GDPR












---


# SOC 2 Type II












---


# HIPAA












---


# Other frameworks and standards












---


# Bubble for Enterprise












---


# Hosting and infrastructure












---


# Dedicated instance












---


# Security and compliance












---


# Single sign-on (SSO)












---


# GDPR












---


# SOC 2 Type II












---


# HIPAA












---


# Other frameworks












---


# Bubble's security features












---


# Admin and collaboration












---


# Priority support



### CORE REFERENCE

# Using the core reference












---


# Bubble's Interface












---


# Design tab












---


# Workflow tab












---


# Data tab












---


# Styles tab












---


# Plugins tab












---


# Settings tab












---


# Logs tab












---


# Template tab












---


# Toolbar












---


# Top and context menu options












---


# Deployment and version control












---


# Deployment & Version Control Dropdown (legacy)







---


# Elements












---


# General Properties












---


# General Properties (Legacy)







---


# Styling Properties












---


# Styling Properties (Legacy)







---


# Responsive Properties












---


# Responsive Properties (Legacy)







---


# Conditional formatting












---


# States












---


# Page Element












---


# Page Element (Legacy)







---


# Visual Elements












---


# Containers












---


# Container Layout Types












---


# Containers (Legacy)







---


# Input Forms












---


# Reusable Elements












---


# Element Templates (legacy)







---


# Workflows












---


# Events












---


# General Events












---


# Element Events












---


# Custom Events












---


# Recurring Event












---


# Trigger Event












---


# Actions












---


# Account












---


# Navigation












---


# Data (Things)












---


# Email












---


# Element












---


# Custom












---


# Data












---


# Data Sources












---


# Operators and comparisons












---


# Search












---


# Privacy












---


# Styles












---


# API












---


# The Bubble API












---


# The Data API












---


# Authentication












---


# Data API endpoints












---


# Data API requests












---


# The Workflow API












---


# The API Connector












---


# Authentication












---


# Adding calls












---


# Bubble-made Plugins












---


# AddtoAny Share Buttons












---


# Airtable












---


# API Connector












---


# Blockspring












---


# Box












---


# Braintree












---


# Bubble App Connector












---


# Chart.js












---


# Circle Music Player












---


# Disqus












---


# DocuSign












---


# Draggable Elements












---


# Dropzone












---


# Facebook












---


# Fitbit












---


# Full Calendar












---


# Google












---


# Google Analytics












---


# Google Optimize












---


# Google Places












---


# Ionic Elements












---


# Ipiphy












---


# iTunes












---


# Slidebar Menu












---


# LinkedIn












---


# Localize Translation












---


# Mailchimp












---


# Mixpanel












---


# Mouse & Keyboard Interactions












---


# Multiselect Dropdown












---


# Olark Live Chat












---


# OneSignal Web Notifications












---


# Pexels












---


# Progress Bar












---


# reCAPTCHA












---


# Rich Text Editor












---


# Rich Text Editor (Legacy)







---


# Screenshotlayer












---


# SelectPDF












---


# Slack












---


# Segment












---


# Slick Slideshow












---


# SQL Database Connector












---


# Star Rating












---


# Stripe












---


# Tinder-like Element












---


# Twilio Video Chat












---


# Twitter












---


# Wistia












---


# YouTube












---


# Zapier












---


# Ziggeo












---


# Pinterest












---


# Application Settings












---


# App plan












---


# General












---


# Domain / email












---


# Languages












---


# SEO / metatags












---


# API












---


# Collaboration












---


# Sub-apps












---


# Versions












---


### USER MANUAL

# Getting started












---


# What is Bubble?












---


# Building your first app












---


# Planning features












---


# Database structure












---


# Design and UX












---


# Creating and managing apps












---


# The Bubble editor












---


# Tabs and sections












---


# Design tab












---


# The element tree












---


# The property editor












---


# Workflow tab












---


# Data tab












---


# Styles tab












---


# Plugins tab












---


# Settings tab












---


# Application settings












---


# Custom headers/body












---


# Visual settings












---


# Social media sharing












---


# Translating your app












---


# Email settings












---


# Collaboration












---


# Custom domain and DNS












---


# Logs tab












---


# Tools












---


# Key features












---


# The search tool












---


# The issue tracker












---


# The element tree












---


# The element property editor












---


# The debugger












---


# Notes












---


# Previewing your app












---


# Deploying your app












---


# Design












---


# Elements












---


# The element hierarchy












---


# The element tree












---


# The page












---


# Containers












---


# Groups












---


# Repeating groups












---


# Table elements












---


# Popups












---


# Floating groups












---


# Group focus












---


# Visual elements












---


# Input forms












---


# Text and numbers












---


# Dates and time












---


# File uploads












---


# Selection controls












---


# Reusable Elements












---


# Styling












---


# Color variables












---


# Font variables












---


# Styles












---


# Custom Fonts












---


# Responsive design












---


# Building responsive pages












---


# Legacy articles












---


# The Basics (Legacy)







---


# Building Responsive Pages (Legacy)







---


# Migrating Legacy Pages







---


# Tips When Designing (Legacy)







---


# Templates












---


# The Component Library












---


# Importing from Figma












---


# Data












---


# The database












---


# Data types and fields












---


# Creating, saving and deleting data












---


# Finding data












---


# Displaying data












---


# Protecting data with privacy rules












---


# The database editor












---


# Export/import data












---


# Exporting data












---


# Importing data (CSV)












---


# Working with location data












---


# Using Algolia












---


# Database structure by app type












---


# Marketplace Apps












---


# Directory & Listings Apps












---


# Social Network Apps












---


# SaaS Apps












---


# Project Management Apps












---


# CRM Apps












---


# Professional Services Apps












---


# On-demand Apps












---


# Documentation/ CMS Apps












---


# Applicant Tracking System (ATS) Apps












---


# Portfolio Apps












---


# Gallery Apps












---


# Online Store / Ecommerce Apps












---


# Blog Apps












---


# Messaging App












---


# Dashboards












---


# Building Block Apps












---


# Bubble as a backend












---


# Files












---


# Static data












---


# App texts (translations)












---


# Option sets












---


# Temporary data












---


# Custom states












---


# URL parameters












---


# User accounts












---


# Authentication plugins












---


# Facebook plugin












---


# Fitbit plugin












---


# Google plugin












---


# Instagram plugin












---


# Linkedin plugin












---


# Pinterest plugin












---


# Slack plugin












---


# Wistia plugin












---


# YouTube plugin












---


# Cookies set by Bubble












---


# Logic












---


# The frontend and backend












---


# Workflows












---


# Events












---


# Frontend events












---


# Recurring workflows












---


# Custom events












---


# Backend events












---


# Database trigger events












---


# Actions












---


# API Workflows












---


# Dynamic expressions












---


# Conditions












---


# Navigation












---


# Single-page applications (SPA)












---


# Multi-page applications












---


# Page slugs












---


# Maintenance












---


# Collaborators












---


# Version control












---


# Best practices: Version control












---


# Transitioning from the legacy version control












---


# Terminology: Version control












---


# Version Control (legacy)







---


# Commenting












---


# Database maintenance












---


# Copying the database












---


# Restoring database backups












---


# Bulk operations












---


# Wiping change history












---


# Performance












---


# Optimizing for workload












---


# Understanding the workload calculation












---


# Planning for workload












---


# Searches












---


# Page load












---


# Workflows and actions












---


# Backend workflows












---


# Hard limits












---


# Capacity Usage (legacy)







---


# Notes on queries












---


# SEO












---


# Introduction to SEO












---


# SEO: App












---


# SEO: Page












---


# Testing and debugging












---


# Introduction to testing and debugging












---


# The debugger












---


# The server logs












---


# Supported browsers












---


# API workflow scheduler












---


# Integrations












---


# API












---


# Introduction to APIs












---


# What is a RESTful API?












---


# The Bubble API












---


# Bubble API terminology












---


# Authentication












---


# How to authenticate












---


# No authentication












---


# As a User












---


# As an admin












---


# The Data API












---


# Data API Privacy Rules












---


# Data API endpoints












---


# Data API requests












---


# The Workflow API












---


# Workflow API Privacy Rules












---


# Workflow API endpoints












---


# API workflows












---


# Creating API workflows












---


# Scheduling API workflows












---


# Recursive API workflows












---


# API Workflow Scheduler












---


# Case: Stripe notifications












---


# The API Connector












---


# Authentication












---


# Adding calls












---


# Case: Google Translate












---


# How to setup Google API keys












---


# API security












---


# Plugins that connect to APIs












---


# API Glossary












---


# Plugins












---


# What Plugins Can Do












---


# Installing and using Plugins












---


# Authentication plugins












---


# Special Plugins












---


# SQL Database Connector












---


# Bubble App Connector












---


# Infrastructure












---


# Security












---


# Bubble's security features












---


# Planning app security












---


# Client-side and server-side












---


# Bubble account security












---


# App security












---


# Page security












---


# Database security












---


# API security












---


# API Connector security












---


# Data API security












---


# Workflow API security












---


# Cookies












---


# Security checklist












---


# Sub-apps












---


# Bubble release tiers












---


# Hosting and scaling












---


# How Bubble hosting works












---


# Scaling with Bubble












---


# CDN (Cloudflare)












---


# Domain and DNS












---


# Bubble app names












---


# Compliance












---


# GDPR












---


# SOC 2 Type II












---


# HIPAA












---


# Other frameworks and standards












---


# Bubble for Enterprise












---


# Hosting and infrastructure












---


# Dedicated instance












---


# Security and compliance












---


# Single sign-on (SSO)












---


# GDPR












---


# SOC 2 Type II












---


# HIPAA












---


# Other frameworks












---


# Bubble's security features












---


# Admin and collaboration












---


# Priority support



### CORE REFERENCE

# Using the core reference












---


# Bubble's Interface












---


# Design tab












---


# Workflow tab












---


# Data tab












---


# Styles tab












---


# Plugins tab












---


# Settings tab












---


# Logs tab












---


# Template tab












---


# Toolbar












---


# Top and context menu options












---


# Deployment and version control












---


# Deployment & Version Control Dropdown (legacy)







---


# Elements












---


# General Properties












---


# General Properties (Legacy)







---


# Styling Properties












---


# Styling Properties (Legacy)







---


# Responsive Properties












---


# Responsive Properties (Legacy)







---


# Conditional formatting












---


# States












---


# Page Element












---


# Page Element (Legacy)







---


# Visual Elements












---


# Containers












---


# Container Layout Types












---


# Containers (Legacy)







---


# Input Forms












---


# Reusable Elements












---


# Element Templates (legacy)







---


# Workflows












---


# Events












---


# General Events












---


# Element Events












---


# Custom Events












---


# Recurring Event












---


# Trigger Event












---


# Actions












---


# Account












---


# Navigation












---


# Data (Things)












---


# Email












---


# Element












---


# Custom












---


# Data












---


# Data Sources












---


# Operators and comparisons












---


# Search












---


# Privacy












---


# Styles












---


# API












---


# The Bubble API












---


# The Data API












---


# Authentication












---


# Data API endpoints












---


# Data API requests












---


# The Workflow API












---


# The API Connector












---


# Authentication












---


# Adding calls












---


# Bubble-made Plugins












---


# AddtoAny Share Buttons












---


# Airtable












---


# API Connector












---


# Blockspring












---


# Box












---


# Braintree












---


# Bubble App Connector












---


# Chart.js












---


# Circle Music Player












---


# Disqus












---


# DocuSign












---


# Draggable Elements












---


# Dropzone












---


# Facebook












---


# Fitbit












---


# Full Calendar












---


# Google












---


# Google Analytics












---


# Google Optimize












---


# Google Places












---


# Ionic Elements












---


# Ipiphy












---


# iTunes












---


# Slidebar Menu












---


# LinkedIn












---


# Localize Translation












---


# Mailchimp












---


# Mixpanel












---


# Mouse & Keyboard Interactions












---


# Multiselect Dropdown












---


# Olark Live Chat












---


# OneSignal Web Notifications












---


# Pexels












---


# Progress Bar












---


# reCAPTCHA












---


# Rich Text Editor












---


# Rich Text Editor (Legacy)







---


# Screenshotlayer












---


# SelectPDF












---


# Slack












---


# Segment












---


# Slick Slideshow












---


# SQL Database Connector












---


# Star Rating












---


# Stripe












---


# Tinder-like Element












---


# Twilio Video Chat












---


# Twitter












---


# Wistia












---


# YouTube












---


# Zapier












---


# Ziggeo












---


# Pinterest












---


# Application Settings












---


# App plan












---


# General












---


# Domain / email












---


# Languages












---


# SEO / metatags












---


# API












---


# Collaboration












---


# Sub-apps












---


# Versions












---


### ACCOUNT & MARKETPLACE

# Account & Billing












---


# Pricing and workload












---


# What contributes to workload?












---


# Using App Metrics












---


# Plans and billing












---


# Billing cycle












---


# FAQ: Pricing and Workload












---


# Plans & Billing (legacy)







---


# Account Management












---


# Building Apps for Others












---


# Selling on the Marketplace












---


# Official Bubble Certification












---


# Hiring certified developers












---


# Building Plugins












---


# The Plugin Editor












---


# General Settings












---


# Updating to Plugin API v4












---


# Adding API Connections












---


# Building Elements












---


# Building Actions












---


# Loading Data












---


# Publishing & Versioning












---


# Github Integration












---


# Building Templates












---


# Application and data ownership












---


# Bug reports












### PRE-RELEASE

# Dynamic expressions (beta)












---



























