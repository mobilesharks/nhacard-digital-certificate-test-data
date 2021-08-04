[<u>PT</u>](README.md) <u>EN</u>

<h1 align="center">
 NhaCard Certificado Digital
</h1>
<h2 align="center">
 Test Data Repository for NhaCard QR Code Validator mobile application
</h2>

<p align="center">
  <a href="#about">About</a> •
  <a href="#download">Download</a> •
  <a href="#repos">Repos</a> •
  <a href="#tests">Tests</a> •
  <a href="#faqs">FAQs</a>
</p>

## About

Este repositório contêm QR Codes de teste para automatizar os testes da aplicação NhaCard QR Code Validator, a aplicação oficial para Validação de NhaCard Certificados Digitais com leitura de QR Code. 

Todo o processo de validação é feita de forma _offline_ sem implementação de nenhum _Business Rules Engine_ pelo que não valida a veracidade dos dados presentes no certificado sendo a pessoa responsável pela leitura também responsável pela validação dos dados apresentados pelo cidadão com os apresentados na aplicação.

## Download

Obtenha a aplicação NhaCard QR Code Validator através do [Google PlayStore]() (Brevemente).

## Repos

Caso tenha a permissão necessária, aceda o [repositório de desenvolvimento](https://github.com/mobilesharks/nhacard-certificate-validator-android).

## Tests

QR Codes de testes para NhaCard Certificados Digitais:

1. [Certificado válido](CV/1.3.0/1)

2. [Certificado com assinatura digital não reconhecida](CV/1.3.0/2)

3. [Certificado expirado](CV/1.3.0/3)

4. [Conteúdo de QR Code inválido](CV/1.3.0/4)

## FAQs

#### Como usá-lo?
Aponte a câmara do seu dispositivo móvel para ler o código QR do Certificado Digital COVID apresentado. O certificado pode ser apresentado em papel ou em formato digital.
O aplicativo verificará automaticamente o certificado.

Um resultado com luz verde significa que o certificado foi validado com sucesso.
Um resultado com sinal vermelho significa que o certificado não foi validado, sendo apresentado o motivo.

#### Proteção contra COVID 19
Este aplicativo não garante a segurança do titular do Certificado Digital COVID em relação ao COVID-19, nem a sua identidade, servindo apenas para validar a autenticidade do certificado.

#### Identificação legal
A apresentação do Certificado Digital COVID não serve como forma de identificação do portador, faltando sempre a apresentação de documento oficial de identificação válido e legítimo.

#### Proteção de Dados Pessoais
O aplicativo não armazena nenhum tipo de dados pessoais.