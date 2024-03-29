---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: info@terais.eu
  # phone: 888 888 88 88
  # address:
  #   street: 450 Serra Mall
  #   city: Stanford
  #   region: CA
  #   postcode: '94305'
  #   country: United States
  #   country_code: US
  # coordinates:
  #   latitude: '37.4275'
  #   longitude: '-122.1697'
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  # office_hours:
  #   - 'Monday 10:00 to 13:00'
  #   - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
   - icon: globe
     icon_pack: fas
     name: https://terais.eu
     link: 'https://terais.eu'
   - icon: twitter
     icon_pack: fab
     name: TERAIS_project
     link: 'https://twitter.com/TERAIS_project'
   - icon: researchgate
     icon_pack: fab
     name: Project TERAIS
     link: https://www.researchgate.net/profile/Project-Terais
   - icon: facebook
     icon_pack: fab
     name: 'Department of Applied Informatics - Comenius University Bratislava'
     link: 'https://www.facebook.com/profile.php?id=100090422512039'

  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  # form:
  #   # provider: netlify
  #   # formspree:
  #   #   id:
  #   # netlify:
  #   #   # Enable CAPTCHA challenge to reduce spam?
  #   #   captcha: false

design:
  columns: '1'
---

<div class="float-md-right w-md-50 pl-0 pl-md-3 pr-0 col-md-6" style="z-index: 1;">
<h2 class="mt-md-2">Subscribe to TERAIS newsletter</h2>
<p>Get updates about the TERAIS project and related activities
by the project partners directly in your inbox.</p>
{{< mailchimp-subscribe
  mc_u="564b7a7fdd61898e25a642887"
  mc_id="35b9df9812"
  mc_v_id="187"
  mc_f_id="00a9e4e6f0"
  legal="By clicking above to subscribe you consent to processing of the provided personal information for the sole purpose of sending you news about the TERAIS project and related activities by the project partners. You also acknowledge that your information will be transferred to Mailchimp for processing. You can unsubscribe at any time by clicking the link in the footer of our emails."
>}}
</div>