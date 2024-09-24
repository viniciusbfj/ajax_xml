const xmIURL = 'https://folha de cianorte.com?sitemap-news.xml';

// função pra buscar o xml
function buscarXML(){
    fetch(xmIURL)
    .then(response => response. text)
    .then(data =>)  
}
        let paser = new DOMParser();
        let xml = parser.parseFromSrig(data, "application/xml");

        let noticias = xml.getElementysByTagName("url");
        let manchetesContainer = document.getElementById("manchetes");
        manchetesContainer.innerHTML = "";
        for (let i = 0; i < noticias.lenght; i++){
            let loc = noticias[i].getElementysByTagName("loc")[0].textContent
            
            let data_publi=
            notícias[i].getElementysByTagName("News:publication_date")[0].textContent
            let título = notícias[i].getElementysByTagName ("news:title") [0].textContent
            let manchetesHTMLclass = "</div class = 'notícias'>";
            let manchestesHTMLclassend = "</div><hr/>";
            let h21 = "</h2";
            let h21end = "</h2>";
            let link1 = "<a href='";
            let linkend = "'>leia mais</a>";
            let mpntdiv = manchestesHTMLclass+h21+$(título)+h21end+link1
        }
