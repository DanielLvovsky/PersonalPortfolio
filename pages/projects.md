---
title: Projects - Daniel Lvovsky
display: Projects
subtitle: A list of all of my projects that I have done in the past.
description: A list of all of my projects that I have done in the past.
projects:
  Web Apps/Websites:
    - name: 'RealTalk'
      link: 'https://real-talk.netlify.app/'
      desc: 'A simple social media web app built with Vue.js and Firebase Cloud and Firestore'
      icon: 'tabler:messages'
    - name: 'Lineup'
      link: 'https://line-up.vercel.app/'
      desc: 'A ToDo List/ Team Management Platform built with Next.js, Firebase Cloud and deployed via Vercel'
      icon: 'tabler:subtask'
    - name: 'nSlate'
      link: 'https://nslate.netlify.app/login'
      desc: 'A ToDo List PWA app built with React.js, Firebase authentication and data storage'
      icon: 'tabler:list'
    - name: 'ElectroChat'
      link: 'https://electrochat.netlify.app/'
      desc: 'A simple chat app made with React.js and Socket.io'
      icon: 'tabler:bolt'
    

  Chrome Extensions:
    - name: 'NovaTab'
      link: 'https://novatab.netlify.app/'
      desc: 'A Chrome extension that replaces the default new tab with a completely customizable page'
      icon: 'tabler:layout-grid'
    - name: 'Clear Cache'
      link: 'https://chrome.google.com/webstore/detail/clear-cache/appfmjhoobioppbehccakejenccnlfbi?hl=en&authuser=0'
      desc: 'Clear Cache is a chrome extension that clears browser cache, history, cookies, passwords, etc. All from a click of a button.'
      icon: 'tabler:refresh'
    - name: 'Quick Unsplash'
      link: 'https://chrome.google.com/webstore/detail/quick-unsplash/bcehcdieplbonpeognpgfkpldfknbgkh?hl=en&authuser=0'
      desc: 'Quick Unsplash is a Chrome extension that uses the Unsplash API to fetch image data, download source and details about the image.'
      icon: 'tabler:brand-unsplash'
    - name: 'Listify'
      link: 'https://chrome.google.com/webstore/detail/todo-listlistify/mlighlkbfofpeoeolijmolchjdifcbpo?hl=en&authuser=0'
      desc: 'A simple ToDo List extension for Chrome that uses localStorage to save users data'
      icon: 'tabler:list-check'
    - name: 'Alert for Gmail'
      link: 'https://chrome.google.com/webstore/detail/alert/njaeaemciiokfpolomebdlppcafjchod?hl=en&authuser=0'
      desc: 'Alert for Gmail is a Chrome extension that notifies the user for any new emails that are in the inbox.'
      icon: 'tabler:mail'
    

  Electron Apps:
    - name: 'CryptoTrak'
      link: 'https://cryptotrak.netlify.app/'
      desc: 'A desktop app built with React.js, Electron framework and CryptoCompare API that tracks realtime prices of over 100 cryptocurrencies.'
      icon: 'tabler:currency-ethereum'
      
  VS Code Themes:
    - name: 'Galax Theme'
      link: 'https://marketplace.visualstudio.com/items?itemName=daniel-lvovsky.galax-theme'
      desc: 'A modern dark theme with a vaporwave color palette for all coders out there.'
      icon: 'tabler:planet'
    - name: 'Zoko Theme'
      link: 'https://marketplace.visualstudio.com/items?itemName=daniel-lvovsky.zoko-theme'
      desc: 'A modern dark theme for all coders out there.'
      icon: 'carbon:cafe'
    - name: 'Mint Dark Theme'
      link: 'https://marketplace.visualstudio.com/items?itemName=daniel-lvovsky.mintdark-theme'
      desc: 'A modern and minimalist dark theme with a mint color palette for all coders out there.'
      icon: 'tabler:leaf'
    - name: 'Mint Light Theme'
      link: 'https://marketplace.visualstudio.com/items?itemName=daniel-lvovsky.mintlight-theme'
      desc: 'A modern and minimalist light theme with a mint color palette for all coders out there.'
      icon: 'tabler:leaf' 
   
---

<ListProjects :projects="frontmatter.projects"/>


