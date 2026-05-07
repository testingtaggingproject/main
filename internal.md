# About this project
We're building our own website to generate each tag diagnostic. This will help us build empathy for our users and identify gaps that additional content could help users address.

## Part 1: Launch and test tags
Here are the steps to get started with tag diagnostics and empathize with what our users go through. Use in-product text, Ask Advisor (our AI chat tool), help center articles, videos, blogs, and other resources to figure these things out and document what you learn as you go.

This is meant to pair with what JR created in [TaskFlow](https://taskflow.corp.google.com/workspaces/5127198/backlogs/4971214?sv=open&edit=b%2F496709611).

### Step 1: Launch the website
Go to https://testingtaggingproject.github.io/main/.

### Step 2: What to test
1. Create the following accounts
   * Google Analytics
   * Google Ads dollar-a-day
   * Google Marketing Platform
   * Shopify, Wordpress, Wix, or another content management system (CMS)
1. See tag diagnostics in Data Manager (GADM) and Google Tag Experience (GTE)
1. Send data to any of the products and see the data come through via both
   * the Google tag (GTE)
   * Google Tag Manager (GTM) through a container
1. Generate diagnostics through the following:
   1. Add domains to a Google Analytics configuration
   1. Add a config command to your code
   1. Set up conversion linker through Floodlight
   1. Implement a transaction ID for a purchase event
   1. If there's time: Set up consent mode

## Part 2: Audit existing tag diagnostics messages
Review each [tag diagnostic](https://docs.google.com/spreadsheets/d/1s2kmj77veNJnnHryVhpEGoPZXwVBrYo6ZEJwyCbb3KU/edit?resourcekey=0-dllxEsoE1JDGXcqp2frT_w&gid=1469072484#gid=1469072484) and look for

1. Patterns we can create so content is consistent across the board
1. Information that's missing or too complex for users
1. Where we can have the biggest impact on the user experience

Check with [Rudhra](https://moma.corp.google.com/person/rudrabhatt) that this list is comprehensive. We've created a bunch of new diagnostics and had a lot more user interaction since this list was created.

## Part 3: Take a look at the tag diagnostics data
I've included the qualitative data here and the quantitative data is in the Engineering's data dashboard. Start to work with Eng and PM to get more information about who we're designing for. Look at our personas and identify who we're designing for. Start to map out their journey to the diagnostics. Investigate whether research is needed to help validate your hypotheses or if there are any user tests you can do independently.

## Part 4: Create your final presentation
Collate all the information you've collected (your POV, guidelines, data, etc.) to tell a compelling story about the content and how it improves the user experience.
