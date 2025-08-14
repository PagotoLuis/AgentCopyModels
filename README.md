DESENVOLVIDO EM C# VISUAL STUDIO CODE 2022 - Windows Services

1) Instalar .NETFramework 3.5.
2) Instalar o serviço | sc create "AgentCopyModels" binpath= "c:\caminhodoexecutavel"
		      | sc description "AgentCopyModels" "Este serviço copia modelos para o repositório local a cada 5 minutos"
3) Mudar no serviço para inicio automatico
