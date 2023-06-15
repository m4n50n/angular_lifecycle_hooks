# Ciclo de vida de los componentes

Estos son los pasos de ejecución cuando un componente o directiva entra en pantalla:

| Hook / Class Method         | Description                                                                 |
| --------------------------- | --------------------------------------------------------------------------- |
| ***constructor***           | Se llama antes de cualquier ciclo de vida.                                  |
| ***ngOnChanges***           | Se llama antes de cualquier cambio a una propiedad.                         |
| ***ngOnInit***              | Se llama justo después del constructor.                                     |
| ***ngDoCheck***             | Se llama cada vez que una propiedad del componente o directiva es revisada. |
| ***ngAfterContentInit***    | Después de ngOnInit, cuando el componente es inicializado.                  |
| ***ngAfterContentChecked*** | Se llama después de cada revisión del componente o directiva.               |
| ***ngAfterViewInit***       | Después del ngAfterContentInit.                                             |
| ***ngAfterViewChecked***    | Llamado después de cada revisión de las vistas del componente o directiva.  |
| ***ngOnDestroy***           | Se llama justo antes de que el componente se destruya.                      |
