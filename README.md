
# Cerveza-Artesanal

# Nombre de los integrantes:

Jorge Daniel Benavides Gómez Matrícula: 1931714

Oscar Iván Salinas Jaramillo Matricula: 1928800

Ingrid Valeria Cordero Elizondo Matricula:1972274

---------------------------------------------------------------------------------------------

# Problematica

El Señor Pedro es un emprendedor de cerveza artesanal, registra sus ventas y su inventario en una libreta la cual a veces se le olvida recordar en donde el dejo y también a veces sus ventas no coinciden con el inventario.

-------------------------------------------------------------------------------------------------------------------------------

# Solucion  propuesta
El programa tiene como funcionalidad el poder hacer que el señor Pedro tenga una organización más avanzada mediante a este programa, para ello el programa tendrá distintas funcionalidades como la entrada y salida de productos, los costos de produccion, las ventas, lo que tiene en el inventario y entre otras cosas.

----------------------------------------------------------------------------------------------------------------------

# Propuesta técnica:
Clase Main: 

Se agrego la clase Main con metodos public como String mUsuario y mPass.

Se agrego la clase Main con metodos public como boolean mEsVendedor, mEsAdmin.

# Clase Usuario:

Se agrego la clase usuario con Usuario privados como String mNombre, mPass, mCorreoElectronico. 

Se agrego la clase usuario con Usuario privados como boolean mHizoEncuestaExperiencia, mHizoEncuestaPersonal.

Se agrego la clase usuario con Usuario privados como ArrayList <Encuesta> mListaEncuestas, <String> mListaRoles.

# Clase Producto

Se agrego la clase usuario con Producto privados como String mNombre, mDescripcion. 

Se agrego la clase usuario con Producto privados como Double mCosto, mPrecio.

Se agrego la clase usuario con Producto privados como Int mEnStock.

Se agrego la clase usuario con Producto privados como ImagenIcon mImagen.

# Clase Encuesta:

Se agrego la clase usuario con Encuesta privados como String mNombre, mFecha, mPregunta1, mPregunta2, mPregunta3.

Se agrego la clase usuario con Encuesta privados como Int mRespuesta1, mRespuesta2, mRespuesta3.
 
# FrmLogin

Se agrego al FrmLogin con metodos privados void btnIngresarActionPerformed.

Se agrego al FrmLogin con metodos privados void txtPassActionPerformed.

Se agrego al FrmLogin con metodos privados boolean comprobarCredenciales.

Se agrego al FrmLogin con metodos privados void btenerCredenciales.
# FrmModificarProducto
Se agrego al FrmModificarProducto con métodos public String mNombre, mDescripcion.

Se agrego al FrmModificarProducto con métodos public Double mCosto, mPrecio.

Se agrego al FrmModificarProducto con métodos public Integer mEnStock.

Se agrego al FrmModificarProducto con métodos public ImagenIcon mImagen.

Se agrego al FrmModificarProducto con métodos public void btnModificarActionPerformed.

Se agrego al FrmModificarProducto con métodos public void modificar.

Se agrego al FrmModificarProducto con métodos private void txtCostoKeyTyped.

Se agrego al FrmModificarProducto con métodos private void txtStockKeyTyped.

Se agrego al FrmModificarProducto con métodos private void txtPrecioKeyTyped.

Se agrego al FrmModificarProducto con métodos private void btnExaminarActionPerformed.

Se agrego al FrmModificarProducto con método private void btnBuscarActionPerformed.

Se agrego al FrmModificarProducto con método public boolean productoEncontrado.

Se agrego al FrmModificarProducto con método public boolean productoEsUnico.

Se agrego al FrmModificarProducto con método public void obtenerTexto.

Se agrego al FrmModificarProducto con método public void guardar.

Se agrego al FrmModificarProducto con método public void limpiarCampos.

# FrmMenuPrincipal

Se agrego al FrmMenuPrincipal con método private void btnSalirActionPerformed.

Se agrego al FrmMenuPrincipal con método private void btnModificarUsuarioActionPerformed.

Se agrego al FrmMenuPrincipal con método private void btnVerUsuarioActionPerformed.

Se agrego al FrmMenuPrincipal con método private void btnAgregarProductoActionPerformed.

Se agrego al FrmMenuPrincipal con método private void btnCrearUsuarioActionPerformed.

Se agrego al FrmMenuPrincipal con método private void btnEliminarUsuarioActionPerformed.

Se agrego al FrmMenuPrincipal con método private void btnVerProductoActionPerformed.

Se agrego al FrmMenuPrincipal con método private void btnModificarProductoActionPerformed.

Se agrego al FrmMenuPrincipal con método private void btnEliminarProductoActionPerformed.

Se agrego al FrmMenuPrincipal con método private void btnEncuestaExperienciaAppActionPerformed.

Se agrego al FrmMenuPrincipal con método private boolean comprobarSiHizoEncuestaExperiencia.

Se agrego al FrmMenuPrincipal con método private boolean comprobarSiHizoEncuestaPersonal.

Se agrego al FrmMenuPrincipal con método private void btnCerrarSesionActionPerformed.

Se agrego al FrmMenuPrincipal con método private void btnEncuestaPersonalActionPerformed.

Se agrego al FrmMenuPrincipal con método private void btnEstadisticaProductosActionPerformed.

Se agrego al FrmMenuPrincipal con método private void btnGlobalEncuestaActionPerformed.

Se agrego al FrmMenuPrincipal con método private JTable crearTablaUsuarios.

Se agrego al FrmMenuPrincipal con método private JTable crearTablaProductos.
# FrmModificarUsuario
Se agrego al FrmModificarUsuario con método public String mNombre.

Se agrego al FrmModificarUsuario con método public String mPass.

Se agrego al FrmModificarUsuario con método public String mCorreo.

Se agrego al FrmModificarUsuario con método ArrayList<String> mListaRoles.

Se agrego al FrmModificarUsuario con método public FrmModificarUsuario.

Se agrego al FrmModificarUsuario con método private void btnModificarActionPerformed.

Se agrego al FrmModificarUsuario con método private void btnLimpiarActionPerformed.

Se agrego al FrmModificarUsuario con método private void btnBuscarActionPerformed.

Se agrego al FrmModificarUsuario con método public void obtenerTexto.

Se agrego al FrmModificarUsuario con método public boolean usuarioEncontrado.

Se agrego al FrmModificarUsuario con método public void modificar.

Se agrego al FrmModificarUsuario con método public void limpiarCampos.

Se agrego al FrmModificarUsuario con método public void run.
# FrmVerProducto
Se agrego al FrmVerProducto con método public String mNombre.

Se agrego al FrmVerProducto con método public String mDescripcion.

Se agrego al FrmVerProducto con método public Integer mPosicionLista = 0.

Se agrego al FrmVerProducto con método public Integer mStock.

Se agrego al FrmVerProducto con método public Double mCosto.

Se agrego al FrmVerProducto con método public Double mPrecio.

Se agrego al FrmVerProducto con método public ImageIcon mImagen.

Se agrego al FrmVerProducto con método public FrmVerProducto.

Se agrego al FrmVerProducto con método public void mostrarProductoEnPosicionActual.

Se agrego al FrmVerProducto con método private void txtCostoKeyTyped.

Se agrego al FrmVerProducto con método private void txtStockKeyTyped.

Se agrego al FrmVerProducto con método private void txtPrecioKeyTyped.

Se agrego al FrmVerProducto con método private void btnAnteriorActionPerformed.

Se agrego al FrmVerProducto con método private void btnSiguienteActionPerformed.
# FrmResultadosGlobalesDeEncuestas
Se agregoron al FrmResultadosGlobalesDeEncuestas con métodos int:

    int contadorp1v1 = 0;

    int contadorp1v2 = 0;

    int contadorp1v3 = 0;

    int contadorp1v4 = 0;

    int contadorp1v5 = 0;

    int contadorp2v1 = 0;

    int contadorp2v2 = 0;

    int contadorp2v3 = 0;

    int contadorp2v4 = 0;

    int contadorp2v5 = 0;

    int contadorp3v1 = 0;

    int contadorp3v2 = 0;

    int contadorp3v3 = 0;

    int contadorp3v4 = 0;

    int contadorp3v5 = 0;


Se agrego al FrmResultadosGlobalesDeEncuestas con método public FrmResultadosGlobalesDeEncuestas.

Se agrego al FrmResultadosGlobalesDeEncuestas con método public void llenarConResultadosTabla.

Se agrego al FrmResultadosGlobalesDeEncuestas con método public JFreeChart cargarGraficoResultadoEncuesta.
# FrmEliminarProducto
Se agrego al FrmEliminarProducto con método String mNombre.

Se agrego al FrmEliminarProducto con método String mDescripcion.

Se agrego al FrmEliminarProducto con método Double mCosto.

Se agrego al FrmEliminarProducto con método Double mPrecio.

Se agrego al FrmEliminarProducto con método Integer mEnStock.

Se agrego al FrmEliminarProducto con método ImageIcon mImagen.

Se agrego al FrmEliminarProducto con método public FrmEliminarProducto.

Se agrego al FrmEliminarProducto con método private void btnLimpiarActionPerformed.

Se agrego al FrmEliminarProducto con método private void btnEliminarActionPerformed.

Se agrego al FrmEliminarProducto con método public void eliminar.

Se agrego al FrmEliminarProducto con método private void txtCostoKeyTyped.

Se agrego al FrmEliminarProducto con método private void txtStockKeyTyped.

Se agrego al FrmEliminarProducto con método private void txtPrecioKeyTyped.

Se agrego al FrmEliminarProducto con método private void btnExaminarActionPerformed.

Se agrego al FrmEliminarProducto con método private void btnBuscarActionPerformed.

Se agrego al FrmEliminarProducto con método public boolean productoEncontrado.

Se agrego al FrmEliminarProducto con método public boolean productoEsUnico.

Se agrego al FrmEliminarProducto con método public void obtenerTexto.

Se agrego al FrmEliminarProducto con método public void guardar.

Se agrego al FrmEliminarProducto con método public void limpiarCampos.
# FrmEncuestaPersonal

Se agrego al FrmEncuestaPersonal con método public FrmEncuestaPersonal.

Se agrego al FrmEncuestaPersonal con método private void btnEnviarActionPerformed.

Se agrego al FrmEncuestaPersonal con método private void asociarYaLlenoEncuestaAlUsuario
# FrmEncuestaExperiencia

Se agrego al FrmEncuestaExperiencia con método public FrmEncuestaExperiencia.

Se agrego al FrmEncuestaExperiencia con método private void btnEnviarActionPerformed.

Se agrego al FrmEncuestaExperiencia con método private void asociarYaLlenoEncuestaAlUsuario.
# FrmEliminarUsuario

Se agrego al FrmEliminarUsuario con método public FrmEliminarUsuario.

Se agrego al FrmEliminarUsuario con método private void btnEliminarActionPerformed.

Se agrego al FrmEliminarUsuario con método private void btnLimpiarActionPerformed.

Se agrego al FrmEliminarUsuario con método private void btnBuscarActionPerformed.

Se agrego al FrmEliminarUsuario con método public void obtenerTexto.

Se agrego al FrmEliminarUsuario con método public boolean usuarioEncontrado.

Se agrego al FrmEliminarUsuario con método public void eliminar.

Se agrego al FrmEliminarUsuario con método public void limpiarCampos.
# FrmCrearUsuario
Se agrego al FrmCrearUsuario con método String mNombre.

Se agrego al FrmCrearUsuario con método String mPass.

Se agrego al FrmCrearUsuario con método String mCorreo.

Se agrego al FrmCrearUsuario con método ArrayList<String> mListaRoles.

Se agrego al FrmCrearUsuario con método int mCamposVacios = 0.

Se agrego al FrmCrearUsuario con método public FrmCrearUsuario.

Se agrego al FrmCrearUsuario con método private void btnGuardarActionPerformed.

Se agrego al FrmCrearUsuario con método private void btnLimpiarActionPerformed.

Se agrego al FrmCrearUsuario con método public boolean usuarioEsUnico.

Se agrego al FrmCrearUsuario con método public void obtenerTexto.

Se agrego al FrmCrearUsuario con método public boolean passValida.

Se agrego al FrmCrearUsuario con método public void guardar.

Se agrego al FrmCrearUsuario con método public void limpiarCampos.	





----------------------------------------------------------------------------------------------
[![Whats-App-Image-2021-10-21-at-10-12-38-PM.jpg](https://i.postimg.cc/9Qh1xXvW/Whats-App-Image-2021-10-21-at-10-12-38-PM.jpg)](https://postimg.cc/7fKgh4Hc)
------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------


