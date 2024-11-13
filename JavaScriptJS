document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
        e.preventDefault();

        document.quarySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});