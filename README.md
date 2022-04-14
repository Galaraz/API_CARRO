# API-CARRO


Do site https://www.consultarplaca.com.br/

necesario conta para realizar autenticaçao padrao basic Auth

exemplo de requisiçao 

cosulta simples 
https://api.consultarplaca.com.br/v2/consultarPlaca?placa=(Numero_Da_Placa)



retorno :

{
    "status": "ok",
    "mensagem": "Consulta realizada com sucesso!",
    "data_solicitacao": "2022-04-14 10:26:12",
    "dados": {
        "informacoes_veiculo": {
            "dados_veiculo": {
                "placa": "sua placa",
                "chassi": "seu chassi",
                "ano_frabricacao": "2021",
                "ano_modelo": "2022",
                "marca": "suamarca",
                "modelo": "modelo do veiculo",
                "cor": "cor do veiculo",
                "segmento": "",
                "combustivel": "",
                "procedencia": "",
                "municipio": "",
                "uf_municipio": ""
            },
            "dados_tecnicos": {
                "tipo_veiculo": "",
                "sub_segmento": "",
                "numero_motor": "",
                "numero_caixa_cambio": null,
                "potencia": null,
                "cilindradas": ""
            },
            "dados_carga": {
                "numero_eixos": null,
                "capacidade_maxima_tracao": null,
                "capacidade_passageiro": "",
                "peso_bruto_total": ""
            }
        }
    },
    "request": {
        "placa": "sua placa"
    }
}
