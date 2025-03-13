body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #6a5acd;
    color: white;
    padding: 20px 0;
    text-align: center;
}
document.addEventListener("DOMContentLoaded", () => {
    const serviceItems = document.querySelectorAll('.service-item');
    serviceItems.forEach(item => {
        item.addEventListener('mouseenter', () => {
            item.style.backgroundColor = '#f0f0f0';
        });
        item.addEventListener('mouseleave', () => {
            item.style.backgroundColor = 'white';
        });
    });
});
