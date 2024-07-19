# Etapas

## 1. Separar os servidores que têm processos
https://github.com/automatiza-mg/FGTS-SEE/issues/3

- [Listagem dos processos judiciais](https://docs.google.com/spreadsheets/d/1nr54AaQ_Q5__3BXVOCtkei3MjK13fgKB/edit?gid=1148264353#gid=1148264353) = `RELATORIO SEFIP POR PROCESSOS` 

- [ ] Tratar formato das colunas C,D,E (MASP, CPF, PIS) da [planilha com as respostas do formulário](https://docs.google.com/spreadsheets/d/1Qx1PNIvD_9hB5U8tyq4_l4fnGUv-q8kj5RnRUj011hU/edit?gid=805215967#gid=805215967)= `Formulário Coleta Dados FGTS - Acordo AGE (respostas)`

## 2. Separar os servidores que têm inconsistências
https://github.com/automatiza-mg/FGTS-SEE/issues/4

- [Relatório de inconsistência da CEF](https://cecad365.sharepoint.com/sites/LAB.mg/Documentos%20Compartilhados/Forms/AllItems.aspx?ct=1697475886748&or=OWA%2DNT&cid=5a619ea8%2D387d%2D7e63%2Dd6c9%2D6640b5128402&fromShare=true&ga=1&id=%2Fsites%2FLAB%2Emg%2FDocumentos%20Compartilhados%2FGeneral%2F7%2E%20DCD%2FAutomatiza%2EMG%2FAutomatiza%C3%A7%C3%A3o%20de%20processos%2FSEE%2DFGTS%2DLei100%2F18715615000160%5FRel%5FIncon%5FCad%2Etxt&viewid=11fbe8df%2D9f8b%2D40d9%2Da150%2D7bc4253aca91&parent=%2Fsites%2FLAB%2Emg%2FDocumentos%20Compartilhados%2FGeneral%2F7%2E%20DCD%2FAutomatiza%2EMG%2FAutomatiza%C3%A7%C3%A3o%20de%20processos%2FSEE%2DFGTS%2DLei100)

- [ ] Transformar o formato do arquivo `.txt` para formato estruturado: vide [conversão para excel](https://cecad365.sharepoint.com/:x:/r/sites/LAB.mg/Documentos%20Compartilhados/General/7.%20DCD/Automatiza.MG/Automatiza%C3%A7%C3%A3o%20de%20processos/SEE-FGTS-Lei100/18715615000160_Rel_Incon_Cad.xlsx?d=we8a23446c03f4d0e8e6b737293d0b407&csf=1&web=1&e=cC7uxw)

## 3. Automatizar a conferência de nome, MASP e email em consulta de BO em vez de SISAP
https://github.com/automatiza-mg/FGTS-SEE/issues/5

- disponibilidade servidor com acesso ao universo SEE no B.O.
- [ ] verificar acréscimo de coluna de `e-mail` à consulta BO já existente no projeto da PREVCON

## 4. Rever o código atualmente utilizado para fazer as triagens dos itens acima antes de tentar gerar a chave



## 5. Rever a planilha de controle para tipificar todas as situações de não-geração da chave

- [Cabeçalho-exemplo](https://cecad365.sharepoint.com/:x:/r/sites/LAB.mg/Documentos%20Compartilhados/General/7.%20DCD/Automatiza.MG/Automatiza%C3%A7%C3%A3o%20de%20processos/SEE-FGTS-Lei100/CHAVE%20DE%20MOVIMENTA%C3%87%C3%83O.xlsx?d=w3f9292ddc12643f4aec7d4a8d954d5f7&csf=1&web=1&e=iSQcyU) = `CHAVE DE MOVIMENTAÇÃO`

## 6. Gerar site estático com os manuais e orientações encaminhadas por email



## 7. Acoplar ao código do robô o envio da chave pelo email, ou o link do site estático no qual constará o manual ou orientações de como regularizar a situação cadastral junto à CEF
