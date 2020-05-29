Requisto
Serverless


para instalar

execute npm i serverless -g

depois crie um usuari no aws IAM para gerar as credenciais

para iniciar um projeto execute
serverless create --template aws-nodejs --path nodeless

configure suas credenciais
serverless config credentials -o --provider aws --key=AKIAW7575T3QHAIYYE5Y  --secret 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

para fazer o deploy do codigo
serverless deploy -v

pare remover
serverless remove


