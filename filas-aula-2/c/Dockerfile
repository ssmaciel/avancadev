# Definindo imagem de base
FROM golang:1.15

# Definindo diretório de trabalho
WORKDIR /go/src/app

# Copiando diretório para a imagem
# Como é o WORKDIR poderia também ser: ADD . .
ADD . .

# Executando comando de build
RUN go build

# Definindo comando de inicialização
# Ececuta binário
CMD "./samukamaciel-ms-03" 

EXPOSE 9092