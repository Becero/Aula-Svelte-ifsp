<script>
	import Capa from "./Capa.svelte";
	import Secao from "./Secao.svelte";
	import Rodape from "./Rodape.svelte";

</script>
<Capa />

<Secao titulo="Sobre Mim" centralizarTexto={true}>
<p>
	Sou Analista de Marketing e Ecommerce, e um mochileiro de alma.
</p>
<p>
	Trabalho com campanhas e envolvimento de pessoas com acoes.
</p>
</Secao>

<Secao titulo="Competencia" centralizarTexto={false}>
	<ul>
		<li>
			<strong> Habilidade em Aprender</strong> idiomas, programacao, culinaria.
		</li>
		<li>
			<strong> Capacidade de Analise de comportamento</strong>Utilizando ferramentas e estragetias, como usabilidade, resposta;
		</li>
</Secao>

<Secao titulo="Experiencias">
		<div>
		<h2> Yoga Padma</h2>
		<span> EHEAD, Fevereiro 2020 - atual</span>
		<ul>
			<li>Criar Campanhas</li>
			<li>Moldar e Refazer o site principal</li>
		</ul>
	</div>
	<div>
		<h2> Prime Home Decor</h2>
		<span> Gerente de Ecommerce, Abril 2018</span>
		<ul>
			<li>Criar Campanhas</li>
			<li>Moldar e Refazer o site principal</li>
		</ul>
	</div>
</Secao>
<Rodape /> 

