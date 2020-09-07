---
title: "Services"
layout: default
left_sticky_content: |
  # Our partners trust us to break down complexity, prioritize what’s important, identify high-value opportunities, and frame clear choices, so they can make better bets.
offerings:
  - Research partnerships
  - Scans and reports
  - Scenarios and planning activities
  - Venture assessments
  - Product innovation and prototyping
  - Consequence mapping
  - Public arts works and media production
  - Experiential futures and activations
  - Toolkits and playbooks
  - Foresight education and training
  - Brand development
  - Service innovation
partners:
  - Amazon UX Lab, Advanced Devices Group
  - Autodesk, Office of the CTO
  - Atlantic Filmmakers Cooperative
  - At The Moment
  - Cancer Care Ontario
  - The Conference Board of Canada
  - Element AI
  - Emerald Foods x Future Food Studio
  - H&M Group
  - Info-Tech Research Group
  - Lululemon Athletica
  - MaRS Discovery District
  - Myseum of Toronto
  - Nesta
  - New Harvest x MIT Media Lab
  - Pernod Ricard
  - RBC Ventures
  - SXSW x Mercedes Benz
  - TD Bank
  - The Stories Company
  - Vtape
---

## Foresight is the craft of sensing and responding to complex, uncertain possibilities.

We work with organizations looking to understand how their role in the world is changing. Our partners include global companies, SMEs, startups, VCs, cooperatives, arts organizations, NGOs, and governmental bodies. Our approach to strategic foresight is rigorous and non-dogmatic. We judiciously apply the appropriate sequence of methods to solve the challenge at hand.

At our core is a research-driven approach to creation and strategy. We take the time to frame and reframe problems and their iterative solutions.

We believe in a world of distributed, resilient agents increasing their capacity for collective action. To that end, we strive to make our tools, processes, and knowledge open and available – while also working with clients, applying the tools and methods of strategic foresight to their unique needs and situations.

**Offerings**

<table>
<tbody>
{% for item in page.offerings %}
  {% capture thecycle %}{% cycle 'odd', 'even' %}{% endcapture %}
  {% if thecycle == 'odd' %}
  <tr>  <td> <li>{{ item }}</li></td>
    {% if forloop.last %}
      <td></td> </tr>
    {% endif %}
  {% else %}
  <td> <li>{{ item }}</li></td> </tr>
  {% endif %}
{% endfor %}
</tbody>
</table>

**Clients, partners, and projects**

<table>
<tbody>
{% for item in page.partners %}
  {% capture thecycle %}{% cycle 'odd', 'even' %}{% endcapture %}
  {% if thecycle == 'odd' %}
  <tr>  <td> <li>{{ item }}</li></td>
    {% if forloop.last %}
      <td></td> </tr>
    {% endif %}
  {% else %}
  <td> <li>{{ item }}</li></td> </tr>
  {% endif %}
{% endfor %}
</tbody>
</table>
