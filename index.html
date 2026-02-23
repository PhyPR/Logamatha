// ================================
// APP.JS - Main Application Code
// ================================


// ================================
// 1. CLOCK
// ================================
function startClock() {
    function update() {
        const now = new Date();
        document.getElementById('clock').textContent =
            now.toUTCString();
    }
    update();
    setInterval(update, 1000);
}


// ================================
// 2. POPULATION COUNTER
// ================================
function startPopulation() {
    function calculate() {
        const BASE_POP  = 8045000000;
        const BASE_TIME = new Date('2024-01-01').getTime();
        const seconds   = (Date.now() - BASE_TIME) / 1000;
        const pop       = Math.floor(BASE_POP + seconds * 2.5);
        
        document.getElementById('population').textContent =
            pop.toLocaleString();
    }
    calculate();
    setInterval(calculate, 1000);
}


// ================================
// 3. MAP SETUP
// ================================
let map;
let currentLayer;

function initMap() {

    // Create map centered on world
    map = L.map('map', {
        center: [20, 0],
        zoom: 2,
        zoomControl: true
    });

    // Dark theme tiles (default)
    currentLayer = L.tileLayer(
        'https://{s}.basemaps.cartocdn.com/' +
        'dark_all/{z}/{x}/{y}{r}.png',
        { attribution: '© OpenStreetMap © CARTO' }
    ).addTo(map);

    // Add event markers
    addMarkers();
}

// Switch to dark map
function setDark() {
    map.removeLayer(currentLayer);
    currentLayer = L.tileLayer(
        'https://{s}.basemaps.cartocdn.com/' +
        '
