# COMANDO_JAVASCRPIT

parseFloat() /* 'transdormar em float' */
parseInt() /* 'transformar em int ' */

variavel.toFixed(2) /* 'Deixa o valor com 2 casas apos a virgula' */

setTimeout(() => {}, 200)

const valorFormatado = Intl.NumberFormat('pt-br', {style: 'currency', currency: 'BRL'}).format(atual) /* 'Formatar valor em real' */

/* 'Formatar data em br OBS: so mudar o campo ou mudar de variavel que for receber o valor final se nao da erro, caso rodar num for ou forEach' */
  var formatter = new Intl.DateTimeFormat('pt-BR');
  var date = e.DATAEMISSAO_FORM;
  e.DATAEMISSAOFORMATADA = formatter.format(date);

this.$refs.ALUNO.focusIn(); /* 'Colocar o focus no input pelo refs' */

const uninterceptedAxiosInstance = axios.create(); /* 'Rodar a funcao sem 'aparecer' na tela' */

var regex = new RegExp('^[A-Za-zÀ-ÖØ-öø-ÿ0-9% ]{0,}$') /* 'regex que verifica se tem algum caractere inválido' */


this.count_row_grid_ch_pre.push(this.count_ch_pre); /* 'adicionar um valor em um array' */
