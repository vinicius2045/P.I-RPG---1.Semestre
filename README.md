
package pi_rpg;





import java.util.Random;
import java.util.Scanner;
import java.util.ArrayList;
import java.util.Collections;
import java.util.List;
 public class Código_Egito {
     
    public static int menu(){
        int op;
        do{
        Scanner inpult = new Scanner (System.in);
        System.out.println("==================================== > > > M E N U < < < =========================================");
        System.out.println("");
        System.out.println("                                          1) INSTRUÇÃO ");
        System.out.println("                                          2) JOGAR ");
        System.out.println("                                          3) CREDITOS ");
        System.out.println("                                          4) SAIR ");
        op = inpult.nextInt();
        if (op == 1){
            System.out.println("");
            System.out.println("SEJA BEM VINDO \n"
                            + "nossa historia acontece no deserto do egito por volta de 3100 a.c\n uma aventura muito legal e cheia de desafio\n"
                            + "nessa aventura usamos um tema especifico para criar os desafio 'Sistema De Numeração' uma aventura muito lugal voce irá se amarra\n"
                            + "nossa aventura acontece quando o personagem acaba se perdendo no deserto\n e pra isso voce precisa ficar ligado ele vai precisar de ajuda\n"
                            + "ele vai precisar de ajuda de voce que conduzira o jogo e de alguns elementos que encontra no deserto\n"
                            + "toda dica terá que ser muito bem interpretada pois ajudará muito em sua sequencia no jogo\n"
                            + "As questoes será lançada e voce terá que acerta para continuar avançando no jogo\n"
                            + "PRESTE MUITA ATENÇÃO\n"
                            + "pois alguns desafio caso voce perca, voce morre e voltará do começo\n"
                            + "mas tambem, cada desafio que voce acertará voce irá receber algumas recompensas\n"
                            + "Bom espero que voces tenham gostado da nossa ideia de jogo\n"
                            + "tenho certeza que não irá se arrepender de embarca nessa aventura,\n"
                            + "aqui iremos aprendender muito com os desafios feito para voces, que irá tirar algumas de suas duvidas\n"
                            + "o tema Sistema de Numeração foi escolhido nesse jogo para te auxiliar e ajudar evoluir\n"
                            + "Obrigado pela atenção, nos encontramos no jogo\n"
                            + "ATÉ BREVE.");
        }else if(op == 2){
            System.out.println("   # # # J O G O # # #");
        }else if(op == 3){
            System.out.println("CREDITOS");
            System.out.println("");
                    System.out.println("* * * C R E D I T O S * * *");
                    System.out.println("");
            System.out.println(" ---> VINICIUS VIEIRA ");
            System.out.println(" ---> FELIPE BELLOTO ");
            System.out.println(" ---> RODRIGO MIRANDOLLA ");
        }else if(op == 4){
            System.out.println("Obrigado até mais.");
        }else{
            System.out.println("Opção invalida. ");
            
        }
        }while(op != 2 && op != 4 && op < 4);
        return op;
        
    }
   
 

     public static void main(String[] args) {
       menu();
       
        
        Scanner inpult = new Scanner(System.in);
       
       String pergunta;
       String nome;
       int desafio;
       int opçao;
       
        System.out.println("ACHO QUE ME PERDIR NESSE DESERTO !? ");
        System.out.println("");
        System.out.println("Olá como e seu nome ?");
        nome = inpult.next();
        System.out.println("");
        System.out.println(nome+ " voce que embarca nessa aventura comigo? voce nao irá se arepender.");
        System.out.println("1(Sim) ou 2(Não) ");
        opçao = inpult.nextInt();
        System.out.println("");
        if(opçao == 2){
            System.out.println("Poxa obrigado, nos vemos em breve.");
        }else if(opçao == 1){
            System.out.println("Yes... Legal " + nome + " Então vamos nesssa.");
            System.out.println(nome + " Vou te contar um pouco sobre essa aventura,\n"
                    + "como voce pode perceber estamos perdidos nesse deserto e vou precisar muito\n"
                    + "que voce me ajude a desvendar alguns desafio");
            System.out.println("Temos que ser muito inteligentes pois esses desafio contém\n"
                    + "algumas recompensas, mais também eles pode nos tirar alguns beneficios\n"
                    + "como a água, e isso pode até nos levar a morte, pois sem água no deserto\n"
                    + "e quase que impossivel sobreviver...");
            System.out.println("Vai ser uma aventura muito perigosa, mais tenho certeza que vamos\n"
                    + "chegar em nossa objetivo que e encontra a civilização");
            System.out.println("Pelo que fiquei sabendo de um sabio que encontrei algumas horas atrás\n"
                    + "a maioria dos desafios irão ser de 'Sistema Da Numeração', um assunto que\n"
                    + "eu gosto bastante e vou poder ajudar, " + nome + " voce conhece sobre esse assunto?\n"
                            + "De 0 a 10 qual o seu conhecimento sobre esse tema ? ");
            desafio = inpult.nextInt();
            System.out.println("");
            System.out.println("Legal então vamos nessa temos muitos desafio pela frente...");
            System.out.println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
            System.out.println("H O R A S  D E P O I S...");
            System.out.println("");
            System.out.println(nome+ " Acho que estou vendo uma miragem...\n"
                    + "a sede está me deixando louco, temos pouca água\n"
                    + "meu Deus não e miragem nao e um cacto ");
            System.out.println("(Cacto) - Iae caras... ");
            System.out.println("AHHHAHHHHH MEU DEUS O CACTO FALA COOOORREEEEE SOCORRRROOOOOO ");
            System.out.println("(Cacto) - Calma ai caras, acho que voces estão perdidos no que posso ajuda?\n"
                    + " - Queremos saber aonde fica Algumas das piramides mais proxima ou a civilização,\n"
                    + "Sim estamos perdidos...");
            System.out.println("(Cacto) - Hahahaha Voces estão muito longe da civilização, as piramides voces\n"
                    + "conseguem encontra uma antes de anoitecer, posso ajudar e tenho água acredito que vao precisar.\n"
                    + " - Vamos sim no que podemos ajudar ?\n"
                    + "(Cacto) - Ali de baixo daquela pedra tem um dado pegue ele\n"
                    + " - ok pegamos.\n"
                    + "(Cacto) - Para Cada numero que cair tem uma pergunta, Vou dar uma dica\n"
                    + "E sobre SISTEMAS NUMERICOS...\n"
                    + " - Então e verdade, bem que o sabio me falou...\n"
                    + "(Cacto) - Lembrando que se voces errar a pergunta terão que me dar essa garrafa de água\n"
                    + "que vi ai dentro dessa mochila, se acertar eu te falo o caminho para umas das\n"
                    + "piramedes e tambem lidou uma garrafa de água.\nvoce terá 3 sanches\n Está preparado para o desafio ?");
            System.out.println("Está nervoso ?   HAHAHAHAHAHAH");
            System.out.println(" 1(SIM) ou 2(NÃO) ");
            pergunta = inpult.next();
            int resposta = 0;
            int contador = 0;
            do {
                
                
            System.out.println("");
            System.out.println("     ==================================================  >>> P E R G U N T A <<< ================================================== ");
            System.out.println("");
            System.out.println("Sabemos que numeros Romanos São representado por letras e cada um deles\n"
                    + "tem um valor representado, sendo assim qual das alternativas abaixo está correta?\n"
                    + "\n********************* ALTERNATIVAS ***********************");
                System.out.println("");
            System.out.println("1)- M = 1000, C = 100, X = 4: ");
            System.out.println("2)- XC = 90, L = 30, II = 3");
            System.out.println("3)- LXXX = 80, XXX = 30, LXX = 70");
            System.out.println("4)- VI = 4, III = 3, V = 5");
            resposta = inpult.nextInt();
                   
            
            switch(resposta){
                case 1:
                    System.out.println(" (CACTO ) - VOCE ERROU\n"
                            + "HAHAHAHAAHAHAA");
                    contador = contador +1;
                    break;
                case 2:
                    System.out.println("( CACTO ) - HAHAHAHAH VOCE ERROU ");
                    contador = contador +1;
                    break;
                    
                case 3:
                    System.out.println("(Cacto) - DROGA VOCE ACERTOU...\n"
                            + "Toma aqui a garrafa De água prometida...\n"
                            + "E o caminho mais perto para uma das piramedes e Sentido ao sol\n"
                            + "Voce precisa andar cerca de 3 horas...\n"
                            + "=================================================///////////////===============================================");
                    System.out.println("");
                    break;
                case 4: 
                    System.out.println(" ( CACTO ) - HHAHAHHAHAHAH VOCE ERROU ");
                    contador = contador + 1;
                default:
                    System.out.println("   (CACTO) - Vai me passando a água VOCE PERDEU HAHAHAHAHAHAHA.");
                    }
                     if(resposta == 1){
                  System.out.println("Vamos la ainda tem chances");
                 }else if(resposta == 2 ){
                     System.out.println("Vamos lá ainda tem chances ");
                     }else if (resposta == 4){
                       System.out.println("Vamos lá ainda tem chance");
                       }else if (resposta == 3){
                       System.out.println("     Yess ... Vamos lá continuar nossa aventura.");
                         System.out.println("");
        }else{
                         System.out.println("    (CACTO) - Vai me passando a água Voce perdeu");
                       }
                }while(resposta != 3 && contador < 3);
           
               if(resposta == 3){
                   System.out.println(" -Ufaa ainda bem que conseguimos " + nome + " agora temos um pouco\n"
                           + "mais de água para continua nossa caminhada nesse deserto\n"
                           + "vamos lá não podemos desistir, espero que nao esteja muito longe da PIRAMEDES e que\n"
                           + "aquele cacto maluco falou, espero que esteja falando a verdade. ");
                   System.out.println("");
                   System.out.println("Será que está chegando ?....\n nossa estou ficando muito cansado \n"
                           + "ei...\n olha ali, um camelo ele deve ter algumas informações\n Vamos lá ver...\n"
                           + "(CAMELO) - Voces estão perdido ?\n 1(Sim) ou 2(Não)");
                   desafio = inpult.nextInt();
                   System.out.println("(CAMELO) - Tem algumas recompenças caso voces acerte um Desafio que irei fazer com voce\n"
                           + "voce topa participar desse desafio?\n 1(Sim) ou 2(Não)");
                   desafio = inpult.nextInt();
                   if(desafio == 2){
                       System.out.println("Obrigado Boa viagem, Mais tenho certeza que irão se arrepender.");
                       
                       
                   }else if(desafio == 1){
                       System.out.println("Bom vamos lá.\n Dentro de umas dessas bolsa que carrego nas costa tem algumas recompenças\n"
                               + "caso voce acerte o desaio, lá tem diamantes e garrafas de água \n caso perca o desafio\n"
                               + "Voce terá que deixa essa mochila nas minhas costas com tudo que está dentro dela.\n"
                               + "tem um detalhe voce terá apenas 1 chance!"
                               + "MEU DEUS "+ nome+ " temos que vencer esse Desafio senão morreremos, pois nao vamos conseguir\n"
                                       + "chegar em nosso objetivo sem essa mochila que está com tudo que temos dentro dela\n"
                                       + "(CAMELO) - Então vamos lá vou fazer a pergunta... ");
                       do{
                       System.out.println("");
                       System.out.println("     ================================= > > > > > P E R G U N T A < < < < < ================================= ");
                       System.out.println("");
                       System.out.println("Sabemos que existem alguns sistemas de numeração, um deles e o mais ultilizado\n"
                               + "Pelas maquinas, qual Sistema e esse ?");
                       System.out.println("");
                       System.out.println("*********************** ALTERNATIVAS **********************");
                       System.out.println("");
                       System.out.println("1) Sistema Octal ");
                       System.out.println("2) Sistema Decimal ");
                       System.out.println("3) Sistema Hexidecimal ");
                       System.out.println("4) Sistema Binario ");
                       resposta = inpult.nextInt();
                       System.out.println("");
                       
                       if(resposta == 1 ){
                           contador = contador +1;
                           System.out.println("Voce perdeu vai me Passando sua mochila.");
                           
                       }else if(resposta == 2){
                           contador = contador +1;
                           System.out.println("ERRADA Vai me passando sua mochila.");
                           
                       }else if(resposta == 3){
                           contador = contador +1;
                           System.out.println("Voce ERROU me Passa sua Mochila.");
                           
                       }else if(resposta == 4){
                           
                       }
                       }while(resposta != 4 && contador <3);
                           
                           System.out.println(">>> PARABÉNS <<< Voce acertou...");
                           System.out.println(" (CAMELO) - Pode pegar suas recompensas que eu prometir e seguir Sua viajem...\n"
                                   + "até breve ainda iremos nos encontra nesse deserto ");
                           System.out.println("\n HORAS DEPOIS...\n");
                           System.out.println(nome+ " Já está ficando de noite e ainda não encontramos as piramides\n"
                                   + "Já andamos mais De 3 hora em direção ao sol e ainda não vimos nada,\n"
                                   + "Será que aquele cacto maluco e aquele camelo estava falando a verdade,\n"
                                   + "Daqui a pouco o sol vai embora e vamos ficar sem direção\n"
                                   + "Então e melhor nois corre antes que fique tudo escuro, \n"
                                   + "Esse deserto ja e perigoso de dia imagine de noite.\n"
                                   + "Vamooosss...\n"
                                   + "(Sabio) - Ei jovens\n"
                                   + "Quem chamou ?!\n"
                                   + "Opa olha quem ta aqui o Sabio "+nome+" Esse e o sabio que eu tinha falado que encontrei\n"
                                           + "Voce estavá nos seguindo sabio?\n"
                                           + "(Sabio) - Acompanhei voces em alguns momentos nesse deserto\n"
                                           + "acho que chegou minha hora de ajudar voces\n"
                                           + "Sei que voces vai precisar muito desse Tema Para desvendar uns Desafios\n"
                                           + "Vou ensinar um pouco sobre ele para voces !\n"
                                           + " - Legal vai nos ajudar muito, qual e o Tema ?\n"
                                           + "\n(Sabio) - O tema e sobre o Sistema Binario E o Sistema Decimal\n"
                                           + "'SISTEMA DECIMAL' Foi então que na Índia foi inventado o SISTEMA De Numeraçao Decimal\n"
                                           + "Aproximadamente no século VI , os hindus criaram um sistema com 10 símbolos com a inveção do 0\n"
                                           + "Mas foram os indianos que colocaram esse símbolo no sistema, no final do século VI"
                                           + "Com a introdução do 0 nosso sistema decimal estava completo\n"
                                           + "E os símbolos 0; 1; 2; 3; 4; 5; 6; 7; 8; e 9 são chamados de algarismo\n"
                                           + ", e é de base 10 pois usamos 10 algarismos para formar qualquer número.\n"
                                           + "\n 'SISTEM BINARIO' O sistema binário é o sistema mais utilizado por máquinas,\n"
                                           + "uma vez que os sistemas digitais trabalham internamente com dois estados\n"
                                           + " (ligado/desligado, verdadeiro/falso, aberto/fechado).\n"
                                           + "O sistema binário utiliza os símbolos: 0, 1 \n"
                                           + "sendo cada símbolo designado por bit (binary digit). Assim é um sistema de base 2.");
                           System.out.println("===========EXEMPLO============");
                           System.out.println("1 0 1 1");
                           System.out.println("| | | |---> 1 x 2 = 1 --> Tem peso 1"); 
                           System.out.println("| | |----> 1 x 2¹ = 2 --> Tem o peso 2");
                           System.out.println("| |------> 0 x 2² = 0 --> Tem o peso 4");
                           System.out.println("|--------> 1 x 2³ = 8 --> Tem o peso 8\n");
                           System.out.println("Trata-se de um padrão que se utiliza da combinação de algarismos \n"
                                   + "ou níveis lógicos '0' e '1' para representação de números, caracteres, cores ou informações\n"
                                   + "0, 1, 10, 11,00, 101,..\n"
                                   + "\n"
                                   + "A base é o número dois, e todos os números\n"
                                   + "são escritos a partir de potências do número dois.");
                           System.out.println("(Sabio) - Espero que voces esteja entendido, Esses são alguns dos\n"
                                   + "Sistema de Numeração ainda tem mais alguns que irei ensinar voces mais a frente\n"
                                   + "Agora vou pedir para Voces pegar um papel e um lapis\n"
                                   + "e converter um numero de decimal Para binario\n"
                                   + "quero ver se voces entenderão o que eu os ensinei.\n");
                           System.out.println("");
                           
                                        boolean acertou = false;
                                          List alternativas = new ArrayList();
                                             alternativas.add("110111100"); // resposta correta
                                             alternativas.add("101011111");
                                             alternativas.add("111010000");
                                             alternativas.add("101110110");
                                             alternativas.add("101111111");
                              do {
                                        Collections.shuffle(alternativas);
                                      System.out.println("O decimal para binario de 444 é:");
                                      System.out.println("1) " + alternativas.get(0));
                                      System.out.println("2) " + alternativas.get(1));
                                      System.out.println("3) " + alternativas.get(2));
                                      System.out.println("4) " + alternativas.get(3));
                                      System.out.println("5) " + alternativas.get(4));
                                      System.out.print("Escolha uma alternativa: ");
                                resposta = inpult.nextInt();
                            switch (resposta) {
                              case 1:
          
                             if (alternativas.get(0).equals("110111100")) {
                                System.out.println("Resposta correta!");
                             acertou = true;
                            } else {
                                System.out.println("Resposta incorreta!");
                        }
                              break;
                              case 2:
         
                             if (alternativas.get(1).equals("110111100")) {
                               System.out.println("Resposta correta!");
                               acertou = true;
                           } else {
                               System.out.println("Resposta incorreta!");
                          }
                              break;
                               case 3:
        
                            if (alternativas.get(2).equals("110111100")) {
                              System.out.println("Resposta correta!");
                              acertou = true;
                         } else {
                              System.out.println("Resposta incorreta!");
                       }
                               break;
                                case 4:
         
                           if (alternativas.get(3).equals("110111100")) {
                             System.out.println("Resposta correta!");
                               acertou = true;
                       } else {
                              System.out.println("Resposta incorreta!");
            }
                              break;
                               case 5:
            
                        if (alternativas.get(4).equals("110111100")) {
                            System.out.println("Resposta correta!");
                           acertou = true;
                    } else {
                             System.out.println("Resposta incorreta!");
        }
                               break;
                              default:
                          System.out.println("Escolha inválida!");
    }
                      } while (!acertou);
                              System.out.println("(SABIO) - Espero que voces tente fazer cade vez mais\n"
                                      + "Pois a repetição que te leva a perfeição, estude cade vez mais\n"
                                      + "e se atente pois iremos nos encontra por ai,\n"
                                      + "e vou ensinar muito mais, boa viagem até breve..."
                                      + " - Droga "+ nome+ "ele sumiu e não nos mostrou o caminho.\n"
                                              + "Mais ele nos ajudou bastante com esse ensinamento\n"
                                              + "pois bem vamos seguir\n");
                              System.out.println("YEESSSS Olha lá " + nome + "Estou vendo uma Piramide\n"
                                      + "Parece Que chegamos, vamos Rapido Quero ver O que tem la dentro\n"
                                      + "Estou morrendo de cede e quero descansar\n"
                                      + "\nVamos entra...\n"
                                      + "Legal Bem Que o sabio Falou que teria grande coisas caso nos\n"
                                      + "encontrace uma piramide.\n"
                                      + "Olha aqui tem aguas e Diamantes, isso vai nos ajudar bastante\n"
                                      + "na nossa caminha até a civilização."
                                      + "Olha "+ nome +" Essas paredes contem muitos numeros Romanos\n"
                                              + "isso vai nos ajudar Bastente, e também Contém alguns sinais\n"
                                              + "De como era Representado os numeros Pelos Romanos\n"
                                              + "Ao todo são 7 desenhos diferentes cada um com seu significado\n"
                                              + "Um exemplo e esse aqui que parece uma corda enrolada\n"
                                              + "Ela representa Uma centena, outro exemplo\n"
                                              + "E Esse traço vertical que representa uma unidade\n"
                                              + "Aqui vamos ter varios Significado, mais agora e o momento\n"
                                              + "De nois descansar para que amnhã continuamos nossa caminhada\n"
                                              + "Ainda estamos muito longe da civilização e temos que descansar\n"
                                              + "Bastante pois a cominhada vai ser longa e desafiadora\n"
                                              + "Bom vou descansar até mais Fui....\n");
                              System.out.println("ZZzzzzzzzZZzzzzZZZZzzzzzZZZZz\n");
                              System.out.println("\nAAAhhhhhh Bom dia " + nome + " Acordei\n"
                                      + "Vamos nessa Que a caminhada e longa");
                              System.out.println("Durante sua caminhada no deserto encontramos uma raposa do deserto\n"
                                      + "E buscamos informação com ela"
                                      + "- Senhora Raposa sabe me dizer a quantos KM eu estou da civilização ?\n"
                                      + "(RAPOSA) - Sei sim porén não será tão facil quanto pensa, ter essa informação\n"
                                      + "eu irei passar em numero binário, assim que eu passar você terá que converter\n"
                                      + " esse numero de binario para decimal, com isso o valor correspontende será a distancia em KM\n"
                                      + "\nEstá Preparado ?\n ");
                              System.out.println("\n=====XXX=====XX=====X===== P E R G U N T A =====X=====XX=====XXX=====\n");
                              do{

                              System.out.println("seu desafio nessa estapa será sobre Sistemas Binário\n "
                                      + "qual seria o número 1010 assim que convertido de Binário para Decimal ?\n");
                              System.out.println(" ****************** A L T E R N A T I V A S *********************");
                              System.out.println("1) - Numero 10 ");
                              System.out.println("2) - Numero 8 ");
                              System.out.println("3) - Numero 9 ");
                              System.out.println("4) - Numero 100 ");
                              resposta = inpult.nextInt();
                              if(resposta == 2){
                                  System.out.println("Voce errou, Preste Atenção");
                              }else if(resposta == 3){
                                  System.out.println("Voce errou, Preste Atenção");
                                  
                              }else if(resposta == 4){
                                  System.out.println("Voce errou, Preste Atenção");
                              }else if(resposta == 1){
                                  System.out.println("BINGOO... Acertou você está a 10 KM da civilização, \n"
                                          + " não perca tempo e vá o mais rápido possivel\n");
                              }
                              }while(resposta != 1 );   
                              System.out.println(" Durante sua caminhada você encontra uma árvore e vai até ela,\n"
                                      + " o sol está escaldante e por esse motivo decidimos descansar.\n"
                                      + " Ao descansar percebe quem tem um pássaro na árvore, \n"
                                      + " então esse pássaro faz uma pergunta: \n"
                                      + "(Passaro ) - O que aconteceu para estár perdido nesse deserto escaldante ?\n"
                                      + " - Olha Sr pássaro eu não sei como vim parar aqui...\n"
                                      + " minha meta é chegar até a civilização e conseguir ajuda.\n"
                                      + "(Passaro) -  Eu irei te ajudar nessa meu amigo(a),\n"
                                      + " poren aqui no deserto a cada um que te passa uma informção você tem que responder uma pergunta...\n"
                                      + "então irei te fazer uma pergunta.?!\n"
                                      + "(Passaro) - Assim que me responder eu aviso as pessoas da civilização virem de encontro a você.\n");
                              System.out.println("=*=*=*=*=*=*=*=*=*=*= P E R G U N T A =*=*=*=*=*=*=*=*=*=*=*=*=*=\n");
                              System.out.println("Os números começaram a existir atraves de contagens de objetos,\n"
                                      + "mas de onde começaram a surgir os números que conhecemos hoje ?\n");
                              System.out.println("------------------>>> A L T E R N A T I V A S <<<-------------------\n");
                              do{
                              System.out.println("1) - Romanos ");
                              System.out.println("2) - Egipicios ");
                              System.out.println("3) - Japoneses ");
                              System.out.println("4) - Ingleses ");
                              resposta = inpult.nextInt();
                              
                              switch(resposta){
                                  case 1:
                                      System.out.println("Poxa cara voce errou !");
                                      break;
                                  case 2:
                                      System.out.println(" - Parabens você acertou, estou indo avisar a civilização que você está perdido\n"
                                              + " vá andando até o norte de encontro a eles... CORRAAA !");
                                      break;
                                  case 3:
                                      System.out.println("Voce Errou, Preste Mais Atenção");
                                      break;
                                  case 4:
                                      System.out.println("Não Voce Errou !");
                                  default:
                                      System.out.println("OPÇÂO INVALIDA");
                              }   
                              }while(resposta != 2);
                              
                            System.out.println(" ApÃ³s alguma horas andando para o Norte, Ã© possÃ­vel avistar uma cÃ¡fila de aproximadamente uns 15 camelos,\n"
                                      + "e em cima de cada camelo, uma pessoa.\n"
                                      + " acima deles, o pÃ¡ssaro que havia feito a Ãºltima pergunta, guiando aquelas pessoas, \n"
                                      + " atÃ© que fosse possÃ­vel encontrar os perdidos no deserto.\n"
                                      + "(Passaro ) - Eu falei que voltaria! Agora vocÃª estÃ¡ a salvo!\n"
                                      + " - Muito obrigado pÃ¡ssaro, como posso retribuir? VocÃª salvou minha vida.\n"
                                      + " (PÃ¡ssaro) - Bem, para isso me reponda portanto uma dÃºvida que tenho,\n"
                                      + "(Passaro) -  Assim nÃ£o deverÃ¡ nenhum favor e nÃ£o terÃ¡ dÃ­vidas com ninguÃ©m.\n");
                                                                     
                                                                                     
                              
                          do{
                       System.out.println("");
                       System.out.println("     ================================= > > > > > P E R G U N T A < < < < < ================================= ");
                       System.out.println("Eu nÃ£o tenho a memÃ³ria muito boa, me ajude a lembrar o nome de um velho amigo?");
                       System.out.println("Ele ficou conhecido por inventar um mÃ©todo para simplificar circuitos lÃ³gicos em eletrÃ´nica digital");
                       System.out.println("Portanto, qual dos estudiosos a seguir foi responsÃ¡vel por tal criaÃ§Ã£o?:");
                       System.out.println("*********************** ALTERNATIVAS **********************");
                       System.out.println("");
                       System.out.println("1) Leonardo Fibonacci ");
                       System.out.println("2) Isaac Newton ");
                       System.out.println("3) PitÃ¡goras ");
                       System.out.println("4) George Boole ");
                       resposta = inpult.nextInt();
                       System.out.println("");
                       
                       if(resposta == 1 ){
                           contador = contador +1;
                           System.out.println("Voce perdeu vai me Passando sua mochila.");
                           
                       }else if(resposta == 2){
                           contador = contador +1;
                           System.out.println("ERRADA Vai me passando sua mochila.");
                           
                       }else if(resposta == 3){
                           contador = contador +1;
                           System.out.println("Voce ERROU me Passa sua Mochila.");
                           
                       }else if(resposta == 4){
                           
                       }
                       }while(resposta != 4 && contador <3);                    
                           
                           System.out.println(">>> PARABÃ‰NS <<< Voce acertou...");
                           System.out.println(" (PÃ¡ssaro) - Agora vocÃª estÃ¡ completamente livre e salvo, e espero jamais que se meta em outra furada...\n"
                                   + "(PÃ¡ssaro) - Acompanhe estes civis, suba na corcova de um dos camelos, e boa recuperaÃ§Ã£o amigo!"
                                   + "(PÃ¡ssaro) - Caso queira relembrar alguns dos assuntos abordados na sua jornada, Ã© sÃ³ me falar\n"
                                   + "(PÃ¡ssaro) - Caso contrÃ¡rio, tenha uma boa viagem!!");
                           
                           do{
                              System.out.println("1) - NÃºmeros Romanos ");
                              System.out.println("2) - NÃºmeros BinÃ¡rios ");
                              System.out.println("3) - Sistemas de NÃºmeraÃ§Ã£o");
                              System.out.println("4) - Ã�lgebra Booleana ");
                              System.out.println("5) - Ir direto Ã  civilizaÃ§Ã£o");
                              resposta = inpult.nextInt();
                              
                              switch(resposta){
                                  case 1:
                                      System.out.println("Os algarismos romanos sÃ£o representados por letras maiÃºsculas,\n"
                                              + " num total de 7 numeraÃ§Ãµes: I (1), V (5), X (10), L (50), C (100), D (500), M (1000).");
                                      break;
                                  case 2:
                                      System.out.println(" Os nÃºmeros binÃ¡rios sÃ£o um sistema baseado em dois algarismos\n"
                                              + ", 0 e 1, que formam a linguagem da informÃ¡tica internacional\n");
                                      break;
                                  case 3:
                                      System.out.println("HÃ¡ registros de vÃ¡rios sistemas de numeraÃ§Ã£o durante a histÃ³ria das civilizaÃ§Ãµes.\n"
                                              + " Com a necessidade de contabilizar, o ser humano desenvolveu a ideia de nÃºmero e\n"
                                              + " a sua representaÃ§Ã£o em algarismos e sistemas de numeraÃ§Ã£o\n"
                                              + "AlÃ©m dos sistemas de civilizaÃ§Ãµes passadas como EgÃ­pcios, Romanos, Chineses, etc\n"
                                              + "Hoje em dia os Sistemas mais conhecidos SÃ£o: BinÃ¡rio, Octal, Decimal e Hexademcimal");
                                      break;
                                  case 4:
                                      System.out.println("A lÃ³gica booleana permite apenas dois estados de circuito, como Verdadeiro e Falso.\n"
                                              + " Esses dois estados sÃ£orepresentados por 1 e 0,\n"
                                              + " em que 1 representa o estado \"Verdadeiro\" e 0 representa o estado \"Falso");
                                      break;
                                   
                                  case 5:
                                      System.out.println("EstÃ¡ bem, foi um prazer dividir esses momentos finais com vocÃª\n"
                                              + "Adeus amigo!");
                                  default:
                                      System.out.println("OPÃ‡Ã‚O INVALIDA");
                              }   
                              }while(resposta != 5);                 
                           
                       
                   }
               }
              
       
            
         
            
        } 
    
    }
 }
