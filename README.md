# -Criando-m-quinas-Virtuais-na-Azure

# 🌐 Desafio: Criação de Máquina Virtual no Microsoft Azure

## 📝 Resumo do que foi feito

Neste projeto, realizei a criação e configuração de uma máquina virtual na plataforma Microsoft Azure, com o objetivo de praticar os conceitos aprendidos durante as vídeo-aulas. Além disso, organizei este repositório com anotações, dicas para servir como material de apoio para futuros estudos ou implementações similares.

---

## ⚙️ Etapas seguidas

1. Acessei o portal do Microsoft Azure e iniciei o processo de criação de uma nova máquina virtual.
2. Escolhi o sistema operacional **Windows Server** *(ou Ubuntu, dependendo do seu caso)*.
3. Configurei os parâmetros básicos da VM: nome, região, tipo de instância e grupo de recursos.
4. Defini um nome de usuário e senha para acesso à máquina.
5. Configurei a porta de acesso (**RDP para Windows** ou **SSH para Linux**).
6. Revisei as configurações e finalizei a criação da VM.
7. Após a criação, acessei a máquina virtual para confirmar que estava funcionando corretamente.


---

## 💡 Dicas úteis

- Sempre revise as configurações antes de finalizar a criação da máquina — principalmente as opções de rede e segurança.
- Anote o IP público da sua VM, pois ele será necessário para o acesso remoto.
- Se estiver usando Linux, certifique-se de que a porta SSH (22) está aberta.
- Use o recurso de **grupos de recursos** para manter os recursos organizados e facilitar a exclusão após o teste.
- Para economizar créditos ou evitar cobranças, **não esqueça de desligar ou excluir a VM quando não estiver usando**.

---

## ✅ O que deu certo ou errado

- A criação da máquina virtual foi bem-sucedida e consegui acessá-la sem problemas.
- Inicialmente, tive dificuldades com a porta de acesso remoto (estava bloqueada no firewall), mas consegui resolver ao revisar as configurações de segurança.
- Uma dica que aprendi na prática foi verificar as regras de entrada da **NSG (Network Security Group)**, pois isso pode impedir o acesso à VM mesmo se tudo parecer certo.
- No geral, o processo foi tranquilo após seguir passo a passo as orientações das vídeo-aulas.

---


