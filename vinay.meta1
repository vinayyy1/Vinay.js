let nfts = [];

function mintNFT(title, genre, mainActorActress, releaseYear) {
    let newNFT = {
        title: title,
        genre: genre,
        mainActorActress: mainActorActress,
        releaseYear: releaseYear
    };
    nfts.push(newNFT);
}

function listNFTs() {
    nfts.forEach((nft, index) => {
        console.log(`NFT ${index + 1}:`);
        console.log(`Title: ${nft.title}`);
        console.log(`Genre: ${nft.genre}`);
        console.log(`Main Actor/Actress: ${nft.mainActorActress}`);
        console.log(`Release Year: ${nft.releaseYear}`);
        console.log("-------------------");
    });
}

function getTotalSupply() {
    return nfts.length;
}

mintNFT("The Godfather", "Crime", "Marlon Brando", 1972);
mintNFT("Star Wars", "Science Fiction", "Mark Hamill", 1977);
mintNFT("Titanic", "Romance", "Leonardo DiCaprio", 1997);

listNFTs();
console.log("Total number of NFTs minted:", getTotalSupply());
