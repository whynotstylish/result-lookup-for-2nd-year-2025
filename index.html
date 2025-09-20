<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>2nd Year Result BY R2H</title>
<style>
/* --- tumhara original CSS, bilkul same --- */
... (same CSS jo tumne diya tha) ...
</style>
</head>
<body>
<div class="container">
    <header class="header">
        <div class="logo">
            <div class="logo-icon">♦</div>
            <div class="logo-text">PAK SIM DB</div>
        </div>
        <div class="status">
            <div class="status-dot"></div>
            <span>SYSTEM ONLINE</span>
        </div>
    </header>

    <main class="main-content">
        <h1 class="title">2nd Year Result BY R2H</h1>
        <p class="subtitle">ADVANCED INFORMATION LOOKUP SYSTEM</p>
        <p class="description">SECURE AND RELIABLE PAKISTAN BISE PART II INFORMATION RETRIEVAL SYSTEM</p>

        <div class="search-section">
            <div class="search-title">
                <div class="search-icon">🔍</div>
                <span>DATABASE QUERY</span>
            </div>

            <div class="input-group">
                <label class="input-label">ROLL NUMBER</label>
                <div class="phone-input-container">
                    <input type="text" class="country-code" value="Roll" readonly>
                    <input type="tel" class="phone-input" id="phoneNumber" placeholder="Enter Roll No" maxlength="10">
                </div>
            </div>

            <button class="search-button" id="searchButton">
                <div class="loading" id="loading"></div>
                <span id="buttonText">SEARCH DATABASE</span>
            </button>
        </div>

        <div class="result-section" id="resultSection">
            <div class="result-grid">
                <div class="result-box">
                    <div class="result-box-title">NAME</div>
                    <div class="result-box-data" id="resultName">-</div>
                </div>
                <div class="result-box">
                    <div class="result-box-title">ROLL NUMBER</div>
                    <div class="result-box-data" id="resultCnic">-</div>
                </div>
                <div class="result-box" style="grid-column: 1 / -1;">
                    <div class="result-box-title">RESULT</div>
                    <div class="result-box-data" id="resultAddress">-</div>
                </div>
            </div>
        </div>

        <div class="error-section" id="errorSection">
            <div class="error-title">Error</div>
            <div class="result-data" id="errorData"></div>
        </div>

    </main>

    <footer class="footer">
        <p class="footer-text">DEVELOP BY R2H Team</p>
    </footer>
</div>

<script>
const phoneInput = document.getElementById('phoneNumber');
const searchButton = document.getElementById('searchButton');
const loading = document.getElementById('loading');
const buttonText = document.getElementById('buttonText');
const resultSection = document.getElementById('resultSection');
const errorSection = document.getElementById('errorSection');
const errorData = document.getElementById('errorData');

const resultName = document.getElementById('resultName');
const resultCnic = document.getElementById('resultCnic');
const resultAddress = document.getElementById('resultAddress');

phoneInput.addEventListener('keypress', function(e){
    if(e.key==='Enter') searchDatabase();
});
searchButton.addEventListener('click', searchDatabase);

async function searchDatabase(){
    const roll = phoneInput.value.trim();
    if(!roll){
        showError('Please enter a valid roll number');
        return;
    }

    setLoading(true);
    hideResults();

    try{
        const response = await fetch(`/api/result/${roll}`);
        const data = await response.json();

        if(data.found){
            displayResult({
                name: data.data.name,
                cnic: data.data.roll,
                address: data.data.result
            });
        } else {
            showError("No result found for this roll number.");
        }

    }catch(error){
        console.error('Error:',error);
        showError('Failed to fetch data.');
    }finally{
        setLoading(false);
    }
}

function setLoading(isLoading){
    loading.style.display = isLoading ? 'block':'none';
    buttonText.textContent = isLoading ? 'SEARCHING...' : 'SEARCH DATABASE';
    searchButton.disabled = isLoading;
}

function displayResult(data){
    hideError();
    resultName.textContent = data.name||'-';
    resultCnic.textContent = data.cnic||'-';
    resultAddress.textContent = data.address||'-';
    resultSection.style.display='block';
}

function showError(message){
    hideResults();
    errorData.textContent = message;
    errorSection.style.display='block';
}

function hideResults(){
    resultSection.style.display='none';
}

function hideError(){
    errorSection.style.display='none';
}
</script>
</body>
</html>
