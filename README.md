<img src="./imagens/aws.jpeg" width="50%"/>


# Gerenciamento instâncias EC2 AWS
Resumo do aprendizado sobre AWS para apresentação na DIO

Neste curso foram abordados os seguintes assuntos:

# AWS - introdução e principais conceitos
Um breve histórico da evolução da AWS e suas mudanças durante a história onde também foram apresentados principais conceitos da Cloud:

* Estrutura on-premise, nuvem e híbrida, cada um com suas principais características e limitações.

Importante frisar que cada cenário pode levar a uma ou outra solução dependendo dos objetivos da empresa e restrições orçamentárias

* Conceito de EC2, EBS e S3
Ficou claro que EC2 se refere à maquina virtual no ambiente AWS, com diversas configurações.

Uma ideia interessante é o usar o AMI, que é uma imagem que contém as informações necessárias para configurar e inicializar uma instância no Amazon EC2. Ela inclui o sistema operacional, os softwares necessários e as configurações específicas para o ambiente desejado. Cada AMI também define o mapeamento de dispositivos de bloco (EBS) que serão anexados às instâncias.
Pode-se utilizar uma AMI pré-definida no ambiente ou se criar uma AMI a partir de uma instância EC2 sua e replicar diversas vezes.
A vantagem é que uma nova instância pode ser gerada em instantes e sem erros, minimizando o tempo de implantação substancialmente.
O EBS se refere à uma unidade de armazenamento que é associado à uma instância EC2, podendo conter bancos de dados, imagens ou o que mais necessitar. Vale ressaltar que os preços variam muito com o armazenamento.
Por último, o S3 diz respeito a armazenamento de objetos diversos em grande volume e que não esteja organizados. A diferença é que o EBS é mais rápido e projetado para armazenar sistemas e dados, semelhante a um SSD em um servidor.

Para se dimensionar os recursos a serem contratados, deve-se proceder a um planejamento cuidadoso e estar muito próximo da equipe desenvolvedora para que os custos e performance estejam o mais perto possível do ideal.

Deve-se lembrar que os recursos podem ser aumentados ou diminuídos sempre que houver necessidade e que pagando-se antecipadamente os custos caem.
Algumas vezes há prmoções de recursos "spot" que podem ser interessantes para usar em ambiente de teste onde os custos podem ser 90% menores com uma desvantagem: o recurso pode ser descontinuado a qualquer momento.
Desta forma, deve-se evitar seu uso em ambientes de produção.

Outra forma de baratear o uso da AWS é desligar recursos que não necessitam estar no ar 24x7, a exemplo de ambientes de desenvolvimento que podem ser desligados às 19h e religados às 8h do dia seguinte.

A plataforma AWS se mostrou uma solução viável e prática para grandes e médias empresas que querem ajustar custos e desembolsar somente o que realmente usam, sem se preocupar com gerenciamento de servidores, por exemplo, focando no negócio principal da empresa.
