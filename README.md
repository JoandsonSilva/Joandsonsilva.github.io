# Joandsonsilva.github.io
Site da Taxonomia
<!doctype html>
<html lang="en">
    <head>
            <meta charset="utf-8">
            <title>Curso HTML5 Essencial</title>
    </head>
   
 
    <style>
		body {
			font-family:poppins;
		}
        td {background-color: white}
        
		table { 
			width:700px;
			margin:0 auto;
			border-spacing:0;
			border-right:1px solid white;
			border-bottom:1px solid white;
		}
		
		caption {
			font-size:130%;
			font-weight:bold;
			padding:5px 0;
			background-color:white;
			border:1px solid white;
			border-bottom:none;
		}
		
		tr, td, th {
			border:thin solid white;
			border-bottom:none;
			border-right:none;
			padding:5px;
		}
        #azul {text-align: left; color: white; background-color: midnightblue}
		#i {text-align: left; }
        
		td { 
			text-align:center;
		}
		
		th {
			text-align:left;
		}
		
		thead th {
			text-align:center;
			background-color:white;
		}

		thead tr th:first-child {
			text-align:left;
		}
		
		tfoot td {
			font-size:20px;
			
		}
	
        tbody tr:nth-child(odd){ 
            background-color: #ddd
             }
        
        .coluna1{
            
            background-color: white;
        }
        
        #verde {background-color: green;
        color: white}
        
        #azulb {background-color: deepskyblue; color: white}
        
        #azule {background-color: rgb(0, 0, 68); color: white;}
        #Laranja {background-color: orangered; color: white;}
        #pink {background-color:rgb(246, 29, 246);color: white;}
        #red {background-color: red;color: white}
        
        #T { font-size: 12px; 
   
            background-color: orange; color: white}
        #T:hover {background-color:beige;} 
            a {text-decoration: none;}
        table {
            float: left; 
        }
        table, td, th {border: 0.1px solid rgb(226, 226, 226);}

	</style>

    <body>
		
        <table>
            
            <caption> Programador Web</caption>
            
            <colgroup>
                <col class="coluna1">
              
            </colgroup>
            <tbody>

                <thead>
                   <tr>
                    <!--ID: I1= Significa início 1-->
                    <td id="azul" colspan="13" >Conteúdo</td>
                    <td id="azulb" colspan="2" >CONHECER</td>
                    <td id="verde" colspan="2">  COMPREENDER  </td>
                    <td id="azule" colspan="2">APLICAR</td>
                    <td id="Laranja" colspan="2" >ANALISAR</td>
                    <td id="pink" colspan="2">SINTETIZAR</td>
                    <td id="red" colspan="2">CRIAR</td>
                </tr>
            </thead>
            <thead>
                <tr>
                    <td id="azul" colspan="13">Curso de Programador Web </td>
                    <td id="azulb" colspan="2" rowspan="2">CONHECER</td>
                    <td id="verde" colspan="2">  COMPREENDER  </td>
                    <td id="azule" colspan="2">APLICAR</td>
                    <td id="Laranja" colspan="2" >ANALISAR</td>
                    <td id="pink" colspan="2">SINTETIZAR</td>
                    <td id="red" colspan="2">CRIAR</td>
                </tr>
            </thead>
            
            <thead>
                <tr>
                    <td colspan="0"></td>
                    
                </tr>
                <tr>
                    <td id="subtitle" colspan="30">Introdução a informática</td>
               </tr>
            </thead>
           
            <!--Unidade1-->
            <thead>
                <tr>
                    <td id="azul">Código</td>
                    
                    <td id="T" colspan="12"><a href="páginas/Unidade 1.html" alt="Acesse a primeira unidade" title="Acesse a primeira unidade" target="_blank">Unidade 1</a> </td>
                    
                    
                    <td id="azulb" colspan="2">  CONHECER</td>
                    <td id="verde" colspan="2">  COMPREENDER  </td>
                    <td id="azule" colspan="2">  APLICAR</td>
                    <td id="Laranja"colspan="2"> ANALISAR</td>
                    <td id="pink" colspan="2">   SINTETIZAR</td>
                    <td id="red" colspan="2">    CRIAR</td>
                </tr>
            </thead>
            
            
            
            
            <tr>
                <td id="i" rowspan="2" ><a href="https://docs.google.com/presentation/d/1mbhshqWki8WgoJwcQacgoFunBcbVr9FL0Ib5Q9fFnWA/edit#slide=id.p1">PW02FIC101</a></td> <td colspan="12" rowspan="2">Introdução a informática</td>
                <td id="azulb" colspan="2">
                    
                                    
                    <select id="dlCores" name="cores" form="fCores">
                        <option id="verde" value="verde"> Discutir</option>
                        <option value="azul">azul</option>
                        <option value="amarelo"> amarelo</option>
                
                    </select>
                
            </td>
                <td id="verde" colspan="2">Discutir</td>
                
                
            </tr>
                              
            <tr>
                <td id="azulb" colspan="2">Apontar</td>
                <td id="verde" colspan="2">Discutir</td>
                <td></td>
                <td></td>
                <td></td>
             </tr>
           
            <tr>
                <td rowspan="2">PW02FIC110</td>
                <td colspan="12" rowspan="2">	Evolução de sistemas computadorizados</td>
                <td id="azulb" colspan="2">Definir</td>
                <td id="verde" colspan="2">Identificar</td>
                
            </tr>
            <tr>
                <td id="azulb" colspan="2">Apontar</td>
                <td id="verde" colspan="2">Disctir</td>
              
            </tr>
           
                <tr>
                <td rowspan="2" >PW02FIC120</td>
                <td colspan="12" rowspan="2">		Internet e redes de computadores</td>
                <td id="azulb" colspan="2">Definir</td>
                <td id="verde" colspan="2">Identificar</td>
                
            </tr>
            <tr>
                <td id="azulb" colspan="2">Apontar</td>
                <td id="verde" colspan="2">Disctir</td>
              
            </tr>
            
           
                <tr>
                <td rowspan="2">PW02FIC130</td>
                <td colspan="12" rowspan="2">		Conceito de navegadores, servidores e tipos de conexões</td>
                <td id="azulb" colspan="2">Definir</td>
                <td id="verde" colspan="2">Identificar</td>
                
            </tr>
            <tr>
                <td id="azulb" colspan="2">Apontar</td>
                <td id="verde" colspan="2">Disctir</td>
                
            </tr>
             <!--Unidade2-->
                      
                 <thead>
                <tr>
                    <td colspan="0"></td>
                    
                </tr>
                <tr>
                    <td id="subtitle" colspan="30">Introdução a Programação</td>
               </tr>
            </thead>
           
          
            <thead>
                <tr>
                    <td id="azul">Código</td>
                    <td id="T" colspan="12" ><a href="páginas/Unidade 2.html" alt="Acesse a segunda unidade" title="Acesse a segunda unidade" target="_blank">Unidade 2 </a> </td>

                    <td id="azulb" colspan="2" >CONHECER</td>
                    <td id="verde" colspan="2">  COMPREENDER  </td>
                    <td id="azule" colspan="2">   APLICAR</td>
                    <td id="Laranja" colspan="2"> ANALISAR</td>
                    <td id="pink" colspan="2">   SINTETIZAR</td>
                    <td id="red" colspan="2">   CRIAR</td>
                </tr>
            </thead>
            
            
            
            
            <tr>
                <td id="i" rowspan="2">PW02FIC201</td>   
                <td colspan="12" rowspan="2">Introdução a informática</td>
                <td id="azulb" colspan="2">Definir</td>
                <td id="verde"colspan="2">Discutir</td>
                
                
            </tr>
                              
            <tr>
                <td id="azulb" colspan="2">Apontar</td>
                <td id="verde" colspan="2">Discutir</td>
                <td></td>
                <td></td>
                <td></td>
             </tr>
           
            <tr>
                <td rowspan="2">PW02FIC210</td>
                <td colspan="12" rowspan="2">	Evolução de sistemas computadorizados</td>
                <td id="azulb" colspan="2">Definir</td>
                <td id="verde" colspan="2">Identificar</td>
                
            </tr>
            <tr>
                <td id="azulb" colspan="2">Apontar</td>
                <td id="verde" colspan="2">Disctir</td>
                
            </tr>
           
                <tr>
                <td rowspan="2">PW02FIC220</td>
                <td colspan="12" rowspan="2">		Internet e redes de computadores</td>
                <td id="azulb"colspan="2">Definir</td>
                <td id="verde"colspan="2">Identificar</td>
                
            </tr>
            <tr>
                <td id="azulb"colspan="2">Apontar</td>
                <td id="verde"colspan="2">Disctir</td>
                
            </tr>
            
           
                <tr>
                <td rowspan="2">PW02FIC230</td>
                <td colspan="12" rowspan="2">		Conceito de navegadores, servidores e tipos de conexões</td>
                <td id="azulb"colspan="2">Definir</td>
                <td id="verde"colspan="2">Identificar</td>
                <td id="azule"colspan="2">Ilustrar</td>
                <td id="Laranja"colspan="2">Diferenciar</td>
                
            </tr>
            <tr>
                <td id="azulb"colspan="2">Apontar</td>
                <td id="verde"colspan="2">Disctir</td>
                <td id="azule"colspan="2">Demonstrar</td>
                <td id="Laranja"colspan="2">Calcular</td>
            
            </tr>
            
                <!--Unidade3-->
                      
                <thead>
                    <tr>
                        <td colspan="0"></td>
                        
                    </tr>
                    <tr>
                        <td id="subtitle" colspan="30">Linguagem de marcação</td>
                   </tr>
                </thead>
               
              
                <thead>
                    <tr>
                        <td id="azul">Código</td>
                        <td id="T" colspan="12"><a href="páginas/Unidade 3.html" alt="Acesse a terceira unidade" title="Acesse a terceira unidade" target="_blank">Unidade 3 </a> </td>
                        <td id="azulb" colspan="2" >CONHECER</td>
                        <td id="verde" colspan="2">  COMPREENDER  </td>
                        <td id="azule" colspan="2">APLICAR</td>
                        <td id="Laranja" colspan="2" >ANALISAR</td>
                        <td id="pink" colspan="2">SINTETIZAR</td>
                        <td id="red" colspan="2">CRIAR</td>
                    </tr>
                </thead>
                
                
                
                
                <tr>
                    <td id="i" rowspan="2">PW02FIC180</td>   
                    <td colspan="12" rowspan="2">Linguagem de marcação</td>
                    <td id="azulb" colspan="2">Definir</td>
                    <td id="verde"colspan="2">Discutir</td>
                    
                    
                </tr>
                                  
                <tr>
                    <td id="azulb" colspan="2">Apontar</td>
                    <td id="verde" colspan="2">Discutir</td>
                    <td></td>
                    <td></td>
                    <td></td>
                 </tr>
               
                <tr>
                    <td rowspan="2">PW02FIC190</td>
                    <td colspan="12" rowspan="2">	Evolução de sistemas computadorizados</td>
                    <td id="azulb" colspan="2">Definir</td>
                    <td id="verde" colspan="2">Identificar</td>
                    
                </tr>
                <tr>
                    <td id="azulb" colspan="2">Apontar</td>
                    <td id="verde" colspan="2">Disctir</td>
                    
                </tr>
               
                    <tr>
                    <td rowspan="2">PW02FIC120</td>
                    <td colspan="12" rowspan="2">		Internet e redes de computadores</td>
                    <td id="azulb"colspan="2">Definir</td>
                    <td id="verde"colspan="2">Identificar</td>
                    
                </tr>
                <tr>
                    <td id="azulb"colspan="2">Apontar</td>
                    <td id="verde"colspan="2">Disctir</td>
                    
                </tr>
                
               
                    <tr>
                    <td rowspan="2">PW02FIC120</td>
                    <td colspan="12" rowspan="2">		Conceito de navegadores, servidores e tipos de conexões</td>
                    <td id="azulb"colspan="2">Definir</td>
                    <td id="verde"colspan="2">Identificar</td>
                    
                </tr>
                <tr>
                    <td id="azulb"colspan="2">Apontar</td>
                    <td id="verde"colspan="2">Disctir</td>
                
            

                    <!--Unidade4-->
                      
                 <thead>
                    <tr>
                        <td colspan="0"></td>
                       
                    </tr>
                    <tr>
                         <td id="subtitle" colspan="30">Planejamento visual de sites</td>
                    </tr>
                </thead>
               
              
                <thead>
                    <tr>
                        <td id="azul">Código</td>
                        <td id="T" colspan="12"><a href="páginas/Unidade 4.html" alt="Acesse a quarta unidade" title="Acesse a quarta unidade" target="_blank">Unidade 4 </a> </td>
                        <td id="azulb" colspan="2" >CONHECER</td>
                        <td id="verde" colspan="2">  COMPREENDER  </td>
                        <td id="azule" colspan="2">APLICAR</td>
                        <td id="Laranja" colspan="2" >ANALISAR</td>
                        <td id="pink" colspan="2">SINTETIZAR</td>
                        <td id="red" colspan="2">CRIAR</td>
                    </tr>
                </thead>
                
                
                
                
                <tr>
                    <td id="i" rowspan="2">PW02FIC401</td>   
                    <td colspan="12" rowspan="2">Introdução a informática</td>
                    <td id="azulb" colspan="2">Definir</td>
                    <td id="verde"colspan="2">Discutir</td>
                    
                    
                </tr>
                                  
                <tr>
                    <td id="azulb" colspan="2">Apontar</td>
                    <td id="verde" colspan="2">Discutir</td>
                    <td></td>
                    <td></td>
                    <td></td>
                 </tr>
               
                <tr>
                    <td rowspan="2">PW02FIC410</td>
                    <td colspan="12" rowspan="2">	Evolução de sistemas computadorizados</td>
                    <td id="azulb" colspan="2">Definir</td>
                    <td id="verde" colspan="2">Identificar</td>
                    
                </tr>
                <tr>
                    <td id="azulb" colspan="2">Apontar</td>
                    <td id="verde" colspan="2">Disctir</td>
                    
                </tr>
               
                    <tr>
                    <td rowspan="2">PW02FIC420</td>
                    <td colspan="12" rowspan="2">		Internet e redes de computadores</td>
                    <td id="azulb"colspan="2">Definir</td>
                    <td id="verde"colspan="2">Identificar</td>
                    
                </tr>
                <tr>
                    <td id="azulb"colspan="2">Apontar</td>
                    <td id="verde"colspan="2">Disctir</td>
                    
                </tr>
                
               
                    <tr>
                    <td rowspan="2">PW02FIC430</td>
                    <td colspan="12" rowspan="2">		Conceito de navegadores, servidores e tipos de conexões</td>
                    <td id="azulb"colspan="2">Definir</td>
                    <td id="verde"colspan="2">Identificar</td>
                    
                </tr>
                <tr>
                    <td id="azulb"colspan="2">Apontar</td>
                    <td id="verde"colspan="2">Disctir</td>
                
                
                    <!--Unidade5-->
                          
                    <thead>
                        <tr>
                            <td colspan="0"></td>
                            
                        </tr>
                        <tr>
                            <td id="subtitle" colspan="30">Desenvolvimento de Projeto</td>
                       </tr>
                    </thead>
                   
                  
                    <thead>
                        <tr>
                            <td id="azul">Código</td>
                            <td id="T" colspan="12"><a href="páginas/Unidade 5.html" alt="Acesse a quinta unidade" title="Acesse a quinta unidade" target="_blank">Unidade 5 </a> </td>
                            <td id="azulb" colspan="2" >CONHECER</td>
                            <td id="verde" colspan="2">  COMPREENDER  </td>
                            <td id="azule" colspan="2">APLICAR</td>
                            <td id="Laranja" colspan="2" >ANALISAR</td>
                            <td id="pink" colspan="2">SINTETIZAR</td>
                            <td id="red" colspan="2">CRIAR</td>
                        </tr>
                    </thead>
                    
                    
                    
                    
                    <tr>
                        <td id="i" rowspan="2">PW02FIC501</td>   
                        <td colspan="12" rowspan="2">Introdução a informática</td>
                        <td id="azulb" colspan="2">Definir</td>
                        <td id="verde"colspan="2">Discutir</td>
                        
                        
                    </tr>
                                      
                    <tr>
                        <td id="azulb" colspan="2">Apontar</td>
                        <td id="verde" colspan="2">Discutir</td>
                        <td></td>
                        <td></td>
                        <td></td>
                     </tr>
                   
                    <tr>
                        <td rowspan="2">PW02FIC510</td>
                        <td colspan="12" rowspan="2">	Evolução de sistemas computadorizados</td>
                        <td id="azulb" colspan="2">Definir</td>
                        <td id="verde" colspan="2">Identificar</td>
                        
                    </tr>
                    <tr>
                        <td id="azulb" colspan="2">Apontar</td>
                        <td id="verde" colspan="2">Disctir</td>
                        
                    </tr>
                   
                        <tr>
                        <td rowspan="2">PW02FIC520</td>
                        <td colspan="12" rowspan="2">		Internet e redes de computadores</td>
                        <td id="azulb"colspan="2">Definir</td>
                        <td id="verde"colspan="2">Identificar</td>
                        
                    </tr>
                    <tr>
                        <td id="azulb"colspan="2">Apontar</td>
                        <td id="verde"colspan="2">Disctir</td>
                        
                    </tr>
                    
                   
                        <tr>
                        <td rowspan="2">PW02FIC530</td>
                        <td colspan="12" rowspan="2">		Conceito de navegadores, servidores e tipos de conexões</td>
                        <td id="azulb"colspan="2">Definir</td>
                        <td id="verde"colspan="2">Identificar</td>
                        
                    </tr>
                    <tr>
                        <td id="azulb"colspan="2">Apontar</td>
                        <td id="verde"colspan="2">Disctir</td>
                    
                
            </tdoby>
            
            
            
            <tfoot>
            <tr>
                <td colspan="15">Joandson Silva</td>    
                
            </tr>
            </tfoot>
        </table>
        
    </body>
</html>
