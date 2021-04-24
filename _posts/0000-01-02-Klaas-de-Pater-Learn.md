---
layout: slide
title: "Welcome to our second slide!"
---
<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>
<script>mermaid.initialize({startOnLoad:true});</script>
Check out this diagram:
<div class="mermaid">
sequenceDiagram
    participant Bot
    participant Me
    Bot->>Me: Please follow these steps to publish the website
    loop Gives it a try
        Me->>Me: Follows the steps,<br/>opens the link,<br/>F5's frantically
    end
    Note right of Me: I wonder if I could fix this...
    Me-->>Bot: Well I've done what you asked!
    Bot->>Me: I see you've followed the steps. Check out your website here!
    Me-->>Bot: Jolly good!
</div>
Use the left arrow to go back!