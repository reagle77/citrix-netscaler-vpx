---
copyright:
  years: 1994, 2017
  
lastupdated: "2017-11-02"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Introdução ao dispositivo de software Citrix NetScaler VPX

A implementação de um Citrix NetScaler VPX em sua solução do {{site.data.keyword.BluSoftlayer_notm}} acelera a entrega de aplicativos da web, impulsiona o desempenho e assegura que seus aplicativos e serviços em nuvem permaneçam otimizados, disponíveis e seguros. Se você tiver cargas de trabalho desafiadoras, como jogos, big data e analítica ou nuvens privadas, o Citrix NetScaler VPX poderá ajudá-lo a entregar sua solução quando, onde e como seus usuários precisarem mais.

## Antes
de Começar
Para começar a usar o Citrix NetScaler VPX, será necessário saber as informações a seguir:

* Suas informações de login do Portal do cliente do IBM Cloud
* O local de implementação para o balanceador de carga
* Qual tipo de Netscaler se ajusta melhor às suas necessidades (para obter mais informações, consulte [Explorar Load Balancers](https://console.bluemix.net/docs/infrastructure/loadbalancer-service/explore-load-balancers.html))
* O número de endereços IP públicos necessários
* A VLAN na qual você deseja designar o balanceador de carga

## Solicitando um Citrix NetScaler VPX

Para solicitar um dispositivo de software Citrix NetScaler VPX, navegue para a página de pedido no Portal do cliente:

1. Em seu navegador, abra [Portal do Cliente ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo")](https://control.softlayer.com/){: new_window} e efetue login em sua conta.
2. Na navegação do Portal do cliente, selecione **Dispositivos > Lista de dispositivos** e clique no link **Pedir dispositivos**. 
3. Na página **Pedir produtos e serviços SoftLayer**, role para baixo até a seção Rede e clique no link **Pedir** sob Citrix NetScaler VPX.
4. Selecione um Local no menu suspenso no qual você gostaria de implementar o dispositivo de software Citrix NetScaler VPX.  
5. Selecione o melhor tipo de NetScaler para sua edição de software, versão de software e necessidades de rendimento. 
6. Selecione o número de endereços IP públicos necessários.  
	Estes são endereços IP público estáticos, implementados como endereços IP virtuais (VIPs) no NetScaler VPX.
7. Clique em **Continue**.
8. Insira as informações requeridas por ARIN (ou a organização equivalente em sua região de implementação) para os endereços IP solicitados.
9. Insira suas informações de contato. 
10. Selecione sua VLAN. 
	Para minimizar a latência e assegurar a utilização otimizada de seus recursos de rede, designe o Citrix NetScaler VPX à mesma VLAN dos servidores nos quais o tráfego será distribuído. 
11. Revise o pedido, aceite os termos e clique em **Fazer pedido**. O dispositivo de software Citrix NetScaler VPX é implementado com suas configurações selecionadas. 

## O que vem a seguir

É possível saber mais sobre os [recursos](about-citrix-netscaler-vpx.html) do Citrix Netscaler VPX, revisar a [terminologia](terminology.html) específica do Netscaler ou começar a [configurar](netscaler-basic-configuration.html) o seu Netscaler.
