# 380.-BorderPane
Exercício de bordas 
INICIO
______________________
public class TesteBorderPane extends BorderPane {
	
	public TesteBorderPane() {

		Caixa c1 = new Caixa().comTexto("Topo");
		setTop(c1);
		
		Caixa c2 = new Caixa().comTexto("Esquerda");
		setLeft(c2);
		
		Caixa c3 = new Caixa().comTexto("Direita");
		setRight(c3);
		
		Caixa c4 = new Caixa().comTexto("Fundo");
		setBottom(c4);
		
		Caixa c5 = new Caixa().comTexto("Área Central");
		setCenter(c5);
	}
}

![image](https://user-images.githubusercontent.com/95525963/153307110-8e5c4d17-ce30-4be3-8d4a-e2dd16e3e1bb.png)
