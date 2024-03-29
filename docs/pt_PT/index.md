# Plug-in DynDNS

Este plugin permite que você atualize um serviço DNS dinâmico (dyndns, noip, duckdns,)

# Configuração do plugin 

Depois de baixar o plugin, você só precisa ativá-lo, não há configuração neste nível.

![dyndns](../images/dyndns.PNG)

# Configuração do equipamento 

A configuração do equipamento Dyndns pode ser acessada no menu do plugin :

![dyndns2](../images/dyndns2.PNG)

É assim que a página do plugin Dyndns se parece (aqui com já um dispositivo) :

![dyndns3](../images/dyndns3.PNG)

Depois de clicar em um deles, você obtém :

![dyndns4](../images/dyndns4.PNG)

Aqui você encontra toda a configuração do seu equipamento :

-   **Nome do equipamento dyndns** : nome do seu equipamento DynDns,
-   **Objeto pai** : indica o objeto pai ao qual o equipamento pertence,
-   **Categoria** : categorias de equipamentos (pode pertencer a várias categorias),
-   **Ativar** : torna seu equipamento ativo,
-   **Visivél** : torna seu equipamento visível no painel,
-   **Serviço** : O nome do serviço usado (dyndns.org, noip.com)
-   **Nome do host** : nome completo do DNS a ser atualizado (por exemplo, toto.ddns.net)
-   **Nome de Usuário** : nome de usuário no serviço em questão
-   **Senha** : senha no serviço em questão
-   **Token** : token usado para duckdns
-   **IPv6** : Sua **Serviço** suporta IPv6. Selecione se deseja atualizar sua entrada **Nome do host** Tipo AAAA.

Abaixo você encontra a lista de pedidos :

-   **Nome** : o nome exibido no painel,
-   **Display** : permite exibir os dados no painel,
-   **Teste** : permite testar o comando

> **NOTA**
>
> O Jeedom irá verificar o ip externo a cada 15 minutos; se ele for alterado, o DNS será atualizado

> **IMPORTANTE**
>
> O plug-in fornece um comando para forçar a atualização. Cuidado para não abusar, pois você pode ser temporariamente banido do serviço DNS

> **NOTA**
>
> Se você usa OVH, tenha cuidado para que o nome de usuário esteja na forma mundial.identificador com enquanto o domínio está no formato my-dynHost.mmondomaine.com

> **IPv6**
>
> Você deve ter configurado em seu **Serviço** uma entrada DNS do tipo AAAA para o seu **Nome do host**.
> Tudo **Serviço** não suporta ou fornece informações para IPv6.