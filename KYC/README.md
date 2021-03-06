## KYC-chain

A blockchain based KYC registry prototype

### Descrição do projeto

Os cheques "Conheça seu cliente" Know your customer (KYC) são atualmente um processo extremamente demorado e caro. Negócios dos mais váriados tipos têm de gastar milhões de dólares todos os anos para cumprir os regulamentos KYC ou correm o risco de serem multados. Através de uma rede de blockchain podemos simplificar o processo de KYC reduzindo o custo, aumentando a seguramça e escalabilidade do processo.

O prototipo KYC-chain elimina as verificações KYC redundantes executadas desnecessáriamente, mantendo um banco de dados seguro comum em uma cadeia de blocos. A natureza de uma cadeia de bloqueio garante que as alterações não autorizadas nos dados sejam invalidadas automaticamente. O conceito de prova de reputação torna o processo de verificação mais robusto.

Atualmente o projeto foi testado em uma rede de teste local na qual foi hospedado em alguns laptops pessoais. Portanto, existem algumas limitações em relação à escalabilidade, como o número máximo de bancos que podem ser registrados, que atualmente é limitado a 10. No futuro, planejamos implantar esse registro na rede Ethereum para aumentar sua escalabilidade.

### Descrição do projeto

Os cheques Know your customer (KYC) são atualmente um processo extremamente demorado e caro. As empresas têm de gastar milhões de dólares todos os anos para cumprir os regulamentos KYC ou corre o risco de ser multado pesadamente. Através da rede KYC pretendemos simplificar em grande medida este processo.

A cadeia KYC elimina as verificações KYC redundantes que os bancos realizam atualmente, mantendo um banco de dados seguro comum em uma cadeia de blocos. A natureza de uma cadeia de bloqueio garante que alterações não autorizadas nos dados sejam invalidadas automaticamente. O conceito de prova de reputação torna o processo de verificação mais robusto.

Atualmente, construímos esse registro em uma rede de teste local na qual hospedamos nossos laptops pessoais. Portanto, existem algumas limitações em relação à escalabilidade, como o número máximo de bancos que podem ser registrados, que atualmente é limitado a 10 e assim por diante. No futuro, planejamos implantar esse registro na rede Ethereum para aumentar sua escalabilidade.

### Requerimentos
1. Nodejs - v10.15.3
2. npm - v6.9.0
3. solc - v0.4.26 `npm install solc@0.4.26`
4. web3 - v0.20.1 `npm install web3@0.20.1`
5. ganache-cli - v6.4.3

### Instructions to run
1. Open a terminal window and execute the command line `ganache-cli`.
2. Open another terminal and go to the `root` directory.
3. Execute the `init.js` file using the command line `node init.js`.
4. After about 10-15 seconds, we obtain a 20 byte address. This is the address of the compiled smart contract.
5. Go to the file `root\js\contractDetails.js` and open it using a text editor.
6. Edit the first line denoting the contract instance address given by the variable `contractAddress` to the 20 byte address obtained in step `4`.
7. Now the application is ready for use. Make sure the terminal with `ganache-cli` is up and running. It acts as the local ethereum test network.  

