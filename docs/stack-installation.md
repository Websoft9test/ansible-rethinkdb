# Initial Installation

If you have completed the rethinkdb deployment on Cloud Platform, the following steps is for you to start use it quikly

## Preparation

1. Get the **Internet IP** on your Cloud Platform
2. Check you **[Inbound of Security Group Rule](https://support.websoft9.com/docs/faq/tech-instance.html)** of Cloud Console to ensure the TCP:80 is allowed
3. Make a domain resolution on your DNS Console if you want to use domain for rethinkdb

## rethinkdb Installation Wizard

1. Using local Chrome or Firefox to visit the URL *http://DNS* or *http://Internet IP*, you will enter installation wizard of rethinkdb
   ![](https://libs.websoft9.com/Websoft9/DocsPicture/zh/rethinkdb/rethinkdb-login-websoft9.png)

2. Log in to rethinkdb web console([Don't have password?](/stack-accounts.md#rethinkdb))  
   ![](https://libs.websoft9.com/Websoft9/DocsPicture/zh/rethinkdb/rethinkdb-ok-websoft9.png)

> More useful rethinkdb guide, please refer to [rethinkdb Documentation](https://rethinkdb.com)

## Q&A

#### I can't visit the start page of rethinkdb?

Your TCP:15672 of Security Group Rules is not allowed so there no response from Chrome or Firefox

#### rethinkdb service can't start? 