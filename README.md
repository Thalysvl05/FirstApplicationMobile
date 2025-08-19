# 📱 PrimeiraAplicacaoMobile - App Android SENAC  

![Android Studio](https://img.shields.io/badge/Android%2520Studio-3DDC84.svg?style=for-the-badge&logo=android-studio&logoColor=white)  
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)  
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)  

---

## 🎯 Sobre o Projeto
Este é um aplicativo Android desenvolvido como parte da disciplina **Coding Mobile** do **SENAC**, sob orientação do **Professor Tulago Pinheiro**.  
A aplicação demonstra os conceitos básicos de desenvolvimento Android utilizando **Kotlin** e **XML**.  

---

## 🚀 Funcionalidades
- ✅ **Interface Simples**: Layout clean com um botão centralizado  
- ✅ **Interatividade**: Botão que responde ao clique do usuário  
- ✅ **Feedback Visual**: Exibição de mensagem *Toast* personalizada  
- ✅ **Emulador Configurado**: Pronto para execução no Android Virtual Device (AVD)  

---

## 🛠️ Tecnologias Utilizadas
- **Android Studio** - IDE oficial para desenvolvimento Android  
- **Kotlin** - Linguagem de programação moderna e concisa  
- **XML** - Para construção de layouts  
- **Android SDK** - Software Development Kit para Android  
- **AVD** - Android Virtual Device para emulação  
- **GitHub** - Controle de versão e hospedagem de código  

---

## 📋 Pré-requisitos
Antes de executar o projeto, certifique-se de ter:  

☑️ Android Studio (versão mais recente)  
☑️ SDK do Android configurado  
☑️ Dispositivo virtual (AVD) ou dispositivo físico com depuração USB ativada  
☑️ Conexão com internet para clonar o repositório  

---

## 🚀 Como Executar o Projeto
```bash
PrimeiraAplicacaoMobile/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/myapplication/
│   │   │   │   └── MainActivity.kt
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml
│   │   │   │   └── values/
│   │   │   │       └── strings.xml
│   │   │   └── AndroidManifest.xml
│   │   └── test/
├── gradle/
└── build.gradle
```
🔧 Componentes Principais
MainActivity.kt
kotlin
class MainActivity : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
        val btnMensagen = findViewById<Button>(R.id.btnMensagen)
        btnMensagen.setOnClickListener {
            Toast.makeText(this, "Olá SENAC! Atividade concluída!", Toast.LENGTH_SHORT).show()
        }
    }
}
activity_main.xml
xml
<Button
    android:id="@+id/btnMensagen"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="Clique Aqui!"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintLeft_toLeftOf="parent"
    app:layout_constraintRight_toRightOf="parent"
    app:layout_constraintTop_toTopOf="parent" />

📊 Status do Projeto
✅ Concluído - Todas as funcionalidades solicitadas foram implementadas:
 
Activity única
Botão funcional
Mensagem Toast
Emulador configurado
Repositório GitHub
Documentação completa
 
👨‍🎓 Contexto Acadêmico
Disciplina: Coding - Mobile
Instituição: Faculdade SENAC
Atividade: Prática Individual - Android Studio
Tema: App com 1 Activity, 1 botão e uma mensagem + Emulador + GitHub
 
🤝 Contribuição
Este é um projeto acadêmico individual, mas sugestões e melhorias são sempre bem-vindas!

📞 Contato

Aluno: Thalys Vinícius
GitHub: thalysvl05
E-mail: thalysvl05@gmail.com
