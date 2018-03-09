[![travis build](https://travis-ci.org/78bash/cedarex.svg?branch=master?style=flat)]()
[![hakiri security](https://hakiri.io/github/78bash/cedarex/master.svg?style=flat)]()
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)
[![Join the chat at https://gitter.im/78bash/cedarex](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dwyl/?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![HitCount](http://hits.dwyl.com/78bash/cedarex.svg?style=flat)](http://hits.dwyl.com/78bash/cedarex)

An open-source crypto currency exchange
=======================================

### Introduction 
Welcome to the most advanced peatio release available. Includes various security and UI fixes (more to come).

Specs:
======================================
• Runs, but below minimum specs: 80GB, 2.20GHz, 2GB RAM

• Recomended specs: 300gb SSD, 4x 2.20GHz and 12GB RAM

• Ultra specs: 300gb SSD, 4x 2.20 GHz and 96GB RAM (you can run the OS in RAM its self)

### Recently done / News
• Undergoing fix of security issues.

• Revert config/application.rb

• Revert config/initializers/pusher.rb

• Revert doc/deploy-production-server.md

• Multi Server Support https://github.com/scatterp/peatio/blob/master/MultiServerReadme.md

• Installer with minimal steps [![RELEASE](https://github.com/scatterp/peatio/blob/master/install1.sh)]
wget https://raw.githubusercontent.com/scatterp/peatio/master/install1.sh

$ source install1.sh 

NOTE: it is critical you launch this with "SOURCE" not "SH", not "BASH" etc...
NOTE2: less than 4GB of ram you should disable the line that reads bitcoind or you wont have enough memory to launch the page

• Merge in welcome page from coinxpro.com [![RELEASE]()(https://github.com/scatterp/peatio/https://github.com/scatterp/peatio/tree/testcoinx)]

### Todo (Coming soon in priority order)
• Payment processing.

• Investigate PoxA or socket.io as a pusher replacement.

• All code refactor.

• JRuby compatability and executes faster than previous versions at every step.

• FIX financial information exchange API, added to bring the support of the entire financial eco system allowing for trading clients, banks etc to connect with the exchange.

### Contributions
Contributions will go towards the continued maintenance and enhacement of Cedarex.

#### Bitcoin: 323Ngox37VnPP1tsmFxP5xpmUktsGcaDjE
