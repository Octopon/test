<a id="revokeConsentLink" href="#">Чтобы отозвать согласие, нажмите здесь</a>.

<script>
    document.addEventListener('DOMContentLoaded', function() {
        var revokeConsentLink = document.getElementById('revokeConsentLink');
        revokeConsentLink.addEventListener('click', function(event) {
            event.preventDefault(); // Отменить стандартное действие ссылки

            // Выполнить действие по отзыву согласия
            googlefc.callbackQueue.push(googlefc.showRevocationMessage);
        });
    });
</script>
