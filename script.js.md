document.getElementById('spin-button').addEventListener('click', function() {
    const fruits = ['🍒', '🍋', '🍊', '🍉', '🍇'];
    const slot1 = document.getElementById('slot1');
    const slot2 = document.getElementById('slot2');
    const slot3 = document.getElementById('slot3');
    
    slot1.textContent = fruits[Math.floor(Math.random() * fruits.length)];
    slot2.textContent = fruits[Math.floor(Math.random() * fruits.length)];
    slot3.textContent = fruits[Math.floor(Math.random() * fruits.length)];
});