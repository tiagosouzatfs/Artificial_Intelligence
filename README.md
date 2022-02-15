# Artificial_Intelligence
Repositório da Disciplina de Inteligência Artificial/UFRN - DCA 0200.

<h1>Projeto final</h1>

<p>Implementar dois sistemas Fuzzy, uma com a máquina de inferência Mamdani e outra Sugeno.</p>

<h2>Descrição</h2>

<p>Construi um sistema Fuzzy com 30 regras, entre elas AND e OR em que a saída mostra o nível de frenagem de um pedal de freio de carro, com base nas funções de pertinência de entrada:
  <ul>
    <li>Velocidade do carro: low, average, high
    <li>Distância do carro da frente: small, comfortable, large
    <li>Qualidade da pista: bad, average, good
  </ul>
  E como saída:
  <ul>
    <li>Nível de frenagem do carro: slow, median, fast
  </ul>
</p>

<h3>Execução</h3>

<p>Para a implementação desse projeto, utilizei o Matlab R2018a com a Fuzzy Logic Toolbox.</p>
<p>Para facilitar, foram utilizados os seguintes comandos no terminal do Matlab (Esse comando por ser mais moderno, foi feito na versão R2020a de um colega): 
  <ul>
  <li>mam_fis = readfis('coloque_aqui_o_arquivo_Mamdani.fis_com_o_caminho_do_diretório');
  <li>sug_fis = convertToSugeno(mam_fis);
  </ul>
</p>

<p style="max-width=100%; text-align=center;"><img src="https://github.com/tiagosouzatfs/Artificial_Intelligence/blob/main/Unidade_2/Projeto_2_L%C3%B3gica_Fuzzy/Captura_do_projeto.PNG"></p>
