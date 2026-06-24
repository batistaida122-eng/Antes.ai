!pip install language_tool_python
import language_tool_python

tool = language_tool_python.LanguageTool('pt-BR')

# Cole um texto cheio de erros aqui:
texto_para_corrigir = """
O aluno da faculdade nao sabe a norma ABNT e precisa de ajuda. 
Ele fez o trabalho tudo errado, com erro de portugues e sem formatacao. 
A professora falou que ele nao sabia nada.
"""

print("--- Corrigindo... ---")
texto_corrigido = tool.correct(texto_para_corrigir)

print("\n--- TEXTO FINAL CORRIGIDO ---")
print(texto_corrigido)
