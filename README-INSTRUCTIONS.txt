FOX TREE COFFEE — EVENTS & LOCAL SOURCING UPDATE

This is the complete Netlify-ready website. The ZIP is structured so index.html sits at the root, in the same format as the previous website ZIP.

WHAT HAS BEEN ADDED
-------------------
1. LARGE EVENTS SECTION
- New sales-focused section explaining that Fox Tree can cater for large events.
- Highlights the full mobile bar setup, local craft beer on tap and flexible drinks packages.
- Uses the three supplied event photographs:
  - guests gathered around the trailer
  - the large four-tap mobile bar
  - the fitted Tipsy Fox trailer interior
- Includes a “Discuss your event” button which takes visitors directly to the existing enquiry form.

2. LOCAL SOURCING SECTION
- New “Local names, served from the trailer” section.
- Highweald Wine card using the supplied bottle and glass photograph.
- 360° Brewing Company card using the supplied pint photograph and the Pavilion Helles Lager and Brighton Session IPA artwork.
- roasted Coffee card using the supplied South Downs Blend coffee bag photograph.
- All supplied images have been converted to web-friendly WebP files; the sideways 360° can photographs have also been rotated correctly.

3. NAVIGATION
- Added a “Local sourcing” navigation link.
- The existing “Events” link now takes visitors to the new large-event hire section.
- The previous event video and gallery remain underneath as a separate recent-event showcase.

WHAT HAS BEEN PRESERVED
-----------------------
- Existing homepage design and branding.
- Lindfield Common weekend section.
- Existing event video and gallery.
- Instagram reel.
- Netlify booking enquiry form.
- Thank-you pages and form redirects.
- Email field and Netlify form settings required for enquiries.

HOW TO DEPLOY TO NETLIFY
------------------------
1. Open Netlify and go to the existing Fox Tree Coffee site.
2. Open Deploys.
3. Drag this entire ZIP file into the manual deploy area.
4. Wait for the deploy to finish.
5. Open the live website and hard-refresh with Ctrl + F5.

Do not upload index.html by itself. The whole ZIP must be deployed because the new photographs are inside the assets folder.

FORM EMAIL NOTIFICATIONS
------------------------
The website form is named: booking-enquiry

To send submission notifications to Rufus:
1. Open the site in Netlify.
2. Go to Project configuration.
3. Go to Notifications.
4. Open Form submission notifications.
5. Add an email notification for booking-enquiry, or for all forms.
6. Use: rufus@lloydowen.com
7. Save.

TESTING THE FORM
----------------
1. Test the form on the live Netlify website, not by opening index.html locally.
2. Submit a genuine test enquiry.
3. Confirm that the site opens /thank-you.
4. Check Netlify > Forms > booking-enquiry.
5. Check the notification inbox and junk folder.

IMPORTANT
---------
- Do not remove or rename the assets folder.
- Do not add event.preventDefault() to the booking form JavaScript.
- Keep the field name="email" because Netlify uses it as the reply-to address.
