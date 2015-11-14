
## A Free Website Template for Nonprofits  
We're huge fans of [Github Pages](https://pages.github.com/) and wanted to help nonprofits take advantage of this powerful (and free!) tool. With about an hours worth of work you'll have a published website with the ability to accept online donations.

But most importantly, by hosting your site on Github you'll allow volunteers to easily contribute to ongoing development of your site. Welcome to the world of open source!

___
*Made with :heart: from the folks at [SmarterGiving](https://smartergiving.org)*
___

#### Key Features  
1. Accept online donations  
2. Capture email addresses to begin building your supporter database

#### Demo  
[https://smartergiving.github.io/free-nonprofit-starter-website/](https://smartergiving.github.io/free-nonprofit-starter-website/)

#### Screenshot  
![Screenshot](screenshots/screenshot.png?raw=true "Free Nonprofit Starter Template Screenshot")
___
#### Benefits  
1. **Open Source**  
    Your site and its code will be hosted on Github. This makes it easy for any developer, designer, or copywriter to help customize your site.  

2. **Secure**   
    Accepting online donations shouldn't be taken lightly. The template integrates third party services to handle any and all secure bits.  

3. **No Vendor Lock-In**  
    The third party services we've chosen (for payments and email capture) allow you to transfer your data should you opt for an alternative solution down the road.

___
### Notes
1. This project requires getting your hands a little dirty. If you're looking for a more user-friendly service (albeit paid), we're big fans of [Squarespace](https://squarespace.com).
2. Be sure you understand the [risks of accepting online donations](https://donorbox.org/nonprofit-blog/on-fraud-prevention/). 

___

### Getting Started  
#### Overview  
___
1. Create Github accounts
2. Fork the repo
3. Enter your organization's info in _config.yml
4. Create DonorBox and Stripe accounts (for online donations)  
5. Create TinyLetter account (for email capture)  
6. Enter DonorBox and TinyLetter credentials in `_config.yml`
7. Solicit help from supporters and the open source community  

#### Detailed Tutorial
___
**Step 1** Create Github accounts  

1. Click the green "SignUp" button at the top of this page  
2. Enter your signup information as instructed and click "Create an account"  
3. On the second page ("Choose your Plan"), check the box that says "Help me set up an organization"  

  ![Screenshot](screenshots/signup.jpg?raw=true "Free Nonprofit Starter Template Screenshot")  
4. Follow the remaining steps. Don't forget to confirm your email address.  

___
**Step 2** Fork the repo  

1. Click the "Fork" button at the top of this page
2. When prompted, click the Organization you just set up
3. Change the name of the repo by clicking "Settings" in the right-hand menu. Name the repo "Welcome" and click "Rename".
4. Your site can now be viewed at `[your-organization-name].github.io/welcome`

___
**Step 3** Enter your organization's info

1. Click the `_config.yml` file
2. Click the edit button
3. Enter your information
4. When finished, "commit" the changes by entering a commit message (e.g. "Update config") in the "Commit changes" box at the bottom of the page. Leave the other options as they are, and click the "Commit changes" button.
5. Preview your site at ` [your-organization-name].github.io/welcome`.
6. Continue to adjust `_config.yml` as needed.

___
**Step 4** Create DonorBox account

1. Go to [DonorBox](https://donorbox.org/orgs/new) and create an account.  
2. Be sure to use "Organization Sign Up", which will walk you through creating a [Stripe](https://stripe.com/gallery) account. Stripe handles the actual credit card processing.  
3. Follow the prompts to add your first campaign.

___
**Step 5** Create TinyLetter account  

1. Go to [TinyLetter](http://tinyletter.com/) and create an account by clicking the "Sign Up Free" button  

___
**Step 6** Enter DonorBox and TinyLetter credentials  

1. Edit the `_config.yml` file and enter your credentials in the appropriate spots

  + **Find your DonorBox campaign name**  
After you've created a campaign, on your dashboard click "edit" for the campaign you'd like to include on your site. 2/3rds of the way down the page you'll see a "Form URL" box. This is where you'll find your Donorbox Username for `_config.yml`  
![DonorBox](screenshots/donorbox.jpg?raw=true "DonorBox")   

  + **Find your TinyLetter username**  
Your TinyLetter Username can be found on your Profile page.  
![TinyLetter](screenshots/tinyletter.jpg?raw=true "TinyLetter")

___
**Step 7** Solicit help  

1. Now that your site is online, ask for help from your supporters or the open source community.
2. Places to find help:
  * [HashtagCharity](https://hashtagcharity.org/charities)  
  * [Idealist](http://www.idealist.org/add-org)  
  * [Reddit - NonprofitProjects](https://www.reddit.com/r/nonprofitprojects)  

___
#### Extras  
If you know a little HTML/CSS, the project is built on Bootstrap and offers the full suite of [Bootstrap components](https://smartergiving.github.io/free-nonprofit-starter-website/components-bootstrap.html)
___


### TODOs
- [ ] Simplify tutorial
- [x] Refactor css/sass
- [x] Clean up/eliminate js plugins
- [ ] Move org items from config to _data?
- [ ] Add CNAME and custom domain instructions
- [x] Add links to volunteer matchmaking services (e.g. HashtagCharity)

### Future
- [ ] Google Analytics?
- [ ] Robots meta as option?
- [ ] Ability to handle fiscal sponsorship
- [ ] Add Mailchimp instructions and toggle ability
- [ ] Troubleshooting tips

___

### Credits  
Many thanks to [Xiaoying Riley](https://www.linkedin.com/in/xiaoying) of [3rd Wave Media](http://themes.3rdwavemedia.com/) for the wonderful [open source template](http://themes.3rdwavemedia.com/website-templates/devaid-free-bootstrap-theme-developers/) from which this project is based. License: [Creative Commons Attribution 3.0 License (CC BY 3.0)](http://creativecommons.org/licenses/by/3.0/).

### License

The MIT License (MIT)

Copyright (c) 2015 Chad Kruse, SmarterGiving

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
