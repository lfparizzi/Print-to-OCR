# PrintToOCR
Código integrado com algumas tecnologias que permitem a transferência de um texto em uma imagem ser transcrito diretamente para seu clipboard (Ctrl+C)  
Este código foi desenvolvido com o intuito de me auxiliar no trabalho, por ser Sargento muitas vezes lido diretamente com documentos em PDF, o número identificador dos processos   costuma ser extenso e complexo, com o objetivo de aumentar a produtividade no serviço, desenvolvi este código simples e funcional.  

# 🤔 Como instalar?
Digite os seguintes códigos em seu terminal   
`"pip install pysseract"  `  
`"pip install pyperclip"  `  
`"pip install pyautogui"  `  
`"pip install pynput" `  
clone o repositório ou código.  

# 🚀 PrintToOCR - Como usar?
1- Execute o código.  
2- Imaginemos que vamos selecionar um retângulo em que o texto em formato de imagem esteja compreendido dentro deste retângulo.  
3- Mova o cursor até o canto superior esquerdo deste retângulo imaginário e aperte a tecla "Q".  
4- Agora mova o cursor até o canto inferior direito do retângulo imaginário e aperte novamente a tecla "Q".  
5- Será gerado uma imagem com a área selecionada e o texto que esteja dentro da área será Transcrito pela tecnologia OCR, passando automaticamente para a área de transferência (Ctrl+c).  

# 📈 PrintToOCR - Objetivos futuros
- Implementar um `código listener de Mouse` que possa em conjunto com uma `interface gráfica` criar uma caixa similar ao famoso "selecionar" da área de trabalho do Windows que não interaja com o documento (arrastando ele para o lado ao invés de criar a caixa "selecionar") com o objetivo de tornar seu uso mais intuitivo.
