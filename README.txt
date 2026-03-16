SETUP INSTRUCTIONS
==================
1. Rename your logo file to: owl-logo.jpg
   and place it in the same folder as these HTML files.

2. To deploy for free:
   - Go to netlify.com/drop
   - Drag this entire folder onto the page
   - Your site will be live in ~30 seconds on a temporary URL

3. To connect insightbiodiversity.ca (Rebel.ca DNS):
   - In Netlify: Site Settings > Domain Management > Add custom domain
   - Netlify will give you nameservers (e.g. dns1.p06.nsone.net)
   - In Rebel.ca: Log in > My Domains > Manage DNS > 
     Replace existing nameservers with Netlify's nameservers
   - Allow 24-48 hrs for propagation
   - Netlify auto-provisions free HTTPS/SSL certificate

4. To make .com redirect to .ca:
   - In Netlify: Site Settings > Domain Management > Add insightbiodiversity.com
   - Set it as an alias (redirect) to insightbiodiversity.ca

5. Contact form: The form currently has no backend.
   To activate it: In Netlify, add  data-netlify="true"  to the <form> tag.
   Netlify will handle form submissions and email them to you for free.

Files:
  style.css               - All shared styles
  index.html              - Home page
  about.html              - About / Team
  work.html               - Our Work / Methodology
  data-sovereignty.html   - Data Sovereignty
  partners.html           - Partners & Networks
  contact.html            - Contact
  owl-logo.jpg            - ADD YOUR LOGO FILE HERE
