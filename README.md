<h1>ACTIVE DIRECTORY LAB</h1>

<h2>Descrição</h2>
Simular uma mini rede corporativa onde é possível logar com contas criadas no AD (contas de funcionários) , através do mesmo computador, pois estarão no domínio da empresa.
<br />


<h2>Ferramentas utilizadas</h2>

- <b>Active directory</b> 
- <b>Server Manager 2019</b>
- <b>Virtual Box</b>

<h2>Ambientes usados</h2>

- <b>Windows 10 PRO VM</b> (21H2)

<h2>Como foi feito:</h2>

<p align="center">
Criando a VM que irá ser domínio e adicionando duas interfaces – Internet e Interna: <br/>
 <br>
<img src="https://i.imgur.com/yMJEaWT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://i.imgur.com/Lxok27I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
 Logando na VM: <br/>
 <br>
<img src="https://i.imgur.com/tSMrQZx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
 Acessando o Server Manager: <br/>
 <br>
 <img src="https://i.imgur.com/Cyx6qGC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
 Configurando interfaces de rede dentro do Windows: <br/>
 <img src="https://i.imgur.com/FJ3eqPj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
 Configurando IP da rede interna: <br/>
 <br>
 <img src="https://i.imgur.com/Dx1Pf51.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
 <br>
 Instalando o Active Directory através do Server Manager: <br/>
 <img src="https://i.imgur.com/vjelaQD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
 Criando domínio:  <br/>
 <img src="https://i.imgur.com/WzeWegK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
 Domínio criado:  <br/>
 <img src="https://i.imgur.com/37tbt5v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
 <br>
 Criando uma pasta no AD para armazenar os usuários admins: <br/>
 <img src="https://i.imgur.com/q0nMjsr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
 <br>
 Usuário admin criado dentro do AD: <br/>
 <img src="https://i.imgur.com/iLuOGml.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
 <br>
  Instalando funcionalidade NAT: <br/>
 <img src="https://i.imgur.com/iWvG0qg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
 <br>
  Instalando servidor DHCP: <br/>
 <img src="https://i.imgur.com/R1dKFbS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
 <br>
  Servidor DHCP estabelecido: <br/>
 <img src="https://i.imgur.com/m2oHRw0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
 <br>
  Criando usuários no AD: <br/>
 <img src="https://i.imgur.com/hGfBjRI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
