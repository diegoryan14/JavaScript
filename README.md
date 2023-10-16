# COMANDO_JAVASCRPIT

setTimeout(() => {}, 200)

parseFloat() /* 'transdormar em float' */
parseInt() /* 'transformar em int ' */

/*" Deixa o valor com 2 casas apos a virgula "*/
variavel.toFixed(2)

/*" Formatar valor em real "*/
const valorFormatado = Intl.NumberFormat('pt-br', {style: 'currency', currency: 'BRL'}).format(atual)

/*" Formatar data em br OBS: so mudar o campo ou mudar de variavel que for receber o valor final se nao da erro, caso rodar num for ou forEach "*/
  var formatter = new Intl.DateTimeFormat('pt-BR');
  var date = e.DATAEMISSAO_FORM;
  e.DATAEMISSAOFORMATADA = formatter.format(date);

/*" Transforma a data em data para o grid do syncfusion ordernar certo "*/
  if(e.DATAPREVISTADEPOSITO_FORM != null){
    e.DATAPREVISTADEPOSITO_FORM = new Date(e.DATAPREVISTADEPOSITO_FORM);
  }
  formatoptions: { type: 'dateTime', format: 'dd/MM/y' } /*" Adicionar essa 'variavel' no data "*/
  
/*" Colocar o focus no input pelo refs "*/
  this.$refs.ALUNO.focusIn();

/*" Rodar a funcao sem 'aparecer' na tela "*/
  const uninterceptedAxiosInstance = axios.create();

/*" regex que verifica se tem algum caractere inválido "*/
  var regex = new RegExp('^[A-Za-zÀ-ÖØ-öø-ÿ0-9% ]{0,}$')
  
/*" adicionar um valor em um array "*/
  this.count_row_grid_ch_pre.push(this.count_ch_pre);
