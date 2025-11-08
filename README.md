# buttzeerak57.github.io
<script>
    const noButton = document.querySelector('.no');
    noButton.addEventListener('mouseover', () => {
        const x = Math.random() * (window.innerWidth - 100);
        const y = Math.random() * (window.innerHeight - 50);
        noButton.style.position = 'absolute';
        noButton.style.left = `${x}px`;
        noButton.style.top = `${y}px`;
    });
</script>
