meme_dict = {
    "PAIA" : "Algo sem graça",
    "TANKAR" : "Aguentar, suportar",
    "FLOPAR" : "Falhar, fracassar",
    "FLODAR" : "Em jogos e chats online, é encher o chat com a mesma mensagem"
}

word = input("Digite uma palavra/gíria moderna que você não entende(escreva toda a palavra em letra maiúscula")

if word in meme_dict.keys():
    print(meme_dict[word])

else:
    print("Esta palavra não está inclusa em nosso sistema")
