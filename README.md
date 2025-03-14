#NODE# node-js
    const CEP = 40310000
    fetch(`https://viacep.com.br/ws/${CEP}/json/`).then((response) => {
        return response.json();
    }).then((data) => {
        console.log(data)
    });