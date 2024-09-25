import './lit-components/lit-hello-world';
<lit-hello-world name="Matt"></lit-hello-world>
<demo-component title="New Title" image-src="path/to/your/image.jpg"></demo-component>
#app { display: grid; grid-template-columns: repeat(5, 1fr); } hello-world { grid-column: 1 / 6; } lit-hello-world, .field { grid-column: 1 / 4; } demo-component, .columns { grid-column: 4 / 6; }
