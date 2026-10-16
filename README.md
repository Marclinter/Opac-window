# Opac-window
El zip contiene todo el código fuente. No me hago responsable del uso que le des al programa/The zip file contains all the source code. I am not responsible for how you use the program.

Es un proyecto que hice de carácter autodidacta, con uso de herramientas, es un proyecto que se centra en crear una aplicacion de cifrado local de archivos que a su vez puede modificar estos y previsualizarlos, permite guardar tus archivos en diferentes cajas fuertes y ponerle pings a estas, permite tener varios usuarios, puedes decidir si al abrir la caja fuerte hacer que todos se desencripten de golpe o solo el que selecciones (ideal), permite activar un modo con administrador para que no se puedan borrar tus archivos (opac guard), No soy un profesional, el código no es perfecto y no debes considerar que ofrece una protección mas allá de algo simple o mediano acorde a tus necesidades, aunque los test pasan sadisfactoriamente, es una alfa, aunque pueda salir como beta, esta en fase de desarrollo y sois libres de tomarlo de base para vuestros proyectos dando crédito o de mejorar este existente, me daria un gran honor, no quiero que lo uséis de forma ilegal para ocultar material pirata o pruebas de algo o similar, es un software para la gente que tiene alto riesgo de que le revisen la PC o no quiere que un haker pueda acceder a todo el contenido de esta muy facilmente, y si logro sacar una version en linux (o la hace alguien), podra tambien servir para servidores, es todavia un proyecto algo rudimentario, pero funcional, y por eso lo publico aqui, tambien, no tengo una firma digital, o soy un proovedor reconocido, es normal que windows se alerte porque el ejecutable es un .exe (y tambien algunos antivirus, pues es un software que encripta), no tengais miedo, podeis auditar el codigo con cualquier herramienta.
Virustotal: 1 detección, 3 advertencias.
<img width="919" height="154" alt="image" src="https://github.com/user-attachments/assets/56fffaed-cdb7-4f50-b8fa-db947cecc83b" />
<img width="959" height="493" alt="image" src="https://github.com/user-attachments/assets/598774cd-cb58-41bb-8cf1-66c226207d10" />

This is a self-taught project I developed using various tools. It focuses on creating an application for local file encryption, which also allows for file modification and previewing. You can store files in different "vaults"—each protected by a PIN—and support multiple users. Files are encrypted locally; when opening a vault, you can choose to decrypt everything at once or just the specific file you select (a very useful feature). There is also an "administrator" mode (or "opac guard") that prevents files from being deleted. I am not a professional, and the code is not perfect; please do not assume it offers more than basic to moderate protection, depending on your specific needs. Although it passes all tests, it is currently in an alpha stage—potentially approaching a beta—and is still under active development. You are free to use this as a foundation for your own projects (provided you give credit) or to improve upon the existing code; I would be honored if you did. Please do not use this software for illegal purposes, such as hiding pirated material or concealing evidence. It is intended for individuals at high risk of having their PC inspected, or for those who want to prevent a hacker from easily accessing all the data on their computer. If I manage to release a Linux version (or if someone else creates one), it could also be used for servers. It is still a somewhat rudimentary project, but it is functional—which is why I am sharing it here. Also, I do not have a digital signature, nor am I a recognized vendor; it is normal for Windows to issue a warning because the executable is a .exe file (and also some antivirus programs, since it is software that encrypts). Do not be concerned—you are welcome to audit the code using any tool you choose.
Virustotal: 1 detection, 3 warnings.
<img width="919" height="154" alt="image" src="https://github.com/user-attachments/assets/f1b02206-8dff-4776-9d58-05b0f5f49980" />
<img width="959" height="493" alt="image" src="https://github.com/user-attachments/assets/15c336a3-5668-4022-a170-0ef6aeed7ec9" />

# Uso:
Puedes crear nuevas cajas fuertes dandole al boton de crear caja fuerte 
<img width="835" height="113" alt="image" src="https://github.com/user-attachments/assets/55eacc98-7af7-40ca-b3e4-ef8ecf29c886" />
Y debajo de el aparecera crear clave de descifrado, porque puedes exportar claves de descifrado de una caja a otra, incluso con diferentes usuarios, esta funcion esta algo inmadura a decir verdad.
Una vez en tu caja fuerte puedes darle al mas para crear carpetas, notas, o subir archivos que quieres cifrar, tambien puedes simplemente arrastrarlos dentro 
<img width="221" height="145" alt="image" src="https://github.com/user-attachments/assets/118c5839-df6b-48ff-9fae-f9c458dc28b5" />

En ajustes tienes opciones variadas, todas estan descritas adecuadamente, puedes ir probandolas 
<img width="452" height="529" alt="image" src="https://github.com/user-attachments/assets/a373b954-5bd6-4f93-8459-01cf3b0fa009" />

Aqui explicare algunas cosas, en la funcion añadir pin, que aparece arriba a la derecha como tambien al lado del nombre de la caja, solo añades el pin de la caja en especifico que quieres resguardar, despues, el descifrar al usar es que solo descifre los archivos con los que interactuas, si no descifraria todos los de la caja.
<img width="356" height="103" alt="image" src="https://github.com/user-attachments/assets/32cb7b59-ce8c-4119-997b-632f299a7416" />

# Usage:
You can create new vaults by clicking the "Create vault" button.
<img width="835" height="113" alt="image" src="https://github.com/user-attachments/assets/55eacc98-7af7-40ca-b3e4-ef8ecf29c886" />
Below that, you will see an option to create a decryption key. This allows you to export decryption keys from one vault to another—even between different users—though, to be honest, this feature is still somewhat experimental.
Once inside your vault, you can click the plus (+) icon to create folders or notes, or to upload files you wish to encrypt. You can also simply drag and drop files into the vault.
<img width="221" height="145" alt="image" src="https://github.com/user-attachments/assets/118c5839-df6b-48ff-9fae-f9c458dc28b5" />

The settings menu offers various options, all of which are clearly described; feel free to explore them.
<img width="452" height="529" alt="image" src="https://github.com/user-attachments/assets/a373b954-5bd6-4f93-8459-01cf3b0fa009" />

I’ll clarify a few points here: the "Add PIN" feature—found in the top-right corner as well as next to the vault name—allows you to set a PIN specifically for the vault you want to protect. Additionally, the "decrypt on use" option ensures that only the files you are actively interacting with are decrypted; otherwise, all files in the vault would be decrypted at once. <img width="356" height="103" alt="image" src="https://github.com/user-attachments/assets/32cb7b59-ce8c-4119-997b-632f299a7416" />
