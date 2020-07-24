---
title: 			Board
subtitle:		FOKGZ's Leadership
description:	
permalink:		/board/
---


In accordance with the [Friends of Kyrgyzstan bylaws]({{ site.url }}/bylaws/), there shall be nine members of the Board of Directors consisting of the five members of the executive committee, the three Regional Directors, and the Kyrgyz Director. The members of the Friends of Kyrgyzstan will elect the Board of Directors for a period of two years with the option to continue on for at least two more terms for a maximum of six years. In addition to Kyrgyz RPCVs possible sources for Board members are current Peace Corps volunteers in Kyrgyzstan, staff of the Kyrgyz embassy, academic or business leaders involved with Central Asia. The Board of Directors shall decide all issues relating to national policy and the budget for the Friends of Kyrgyzstan. 

If you are interested in serving on the board, please [contact us]({{ site.url }}/contact/).

## Current board members

<div class="row row-cols-1 row-cols-md-2">
{% for member in site.board %}
  <div class="col-sm-6">
    <div class="card mb-3">
      <div class="card-body">
        <h5 class="card-title">{{ member.name }}, {{ member.position }}</h5>
        <p class="card-text">{{ member.content | markdownify }}</p>
      </div>
    </div>
  </div>
{% endfor %}
</div>