
1. https://ko-fi.com/j0s14s → Tu perfil de Ko-fi


2. https://www.paypal.com/ncp/payment/TV74R9EUSHM3N → Un enlace de pago de PayPal


3. https://ko-fi.com/s/9d7fb1c87a → Un enlace de compra directa en Ko-fi



Si quieres agregar estos enlaces en tu aplicación, podrías hacer algo como esto en tu página principal (index.js):

export default function Home() {
  return (
    <div className="p-6 text-center">
      <h1 className="text-3xl font-bold mb-4">Bienvenido a Josicraft Studio</h1>
      <p className="text-lg mb-4">Compra fondos de pantalla y apoya mi trabajo.</p>

      <div className="flex flex-col gap-4">
        <a
          href="https://ko-fi.com/j0s14s"
          target="_blank"
          rel="noopener noreferrer"
          className="bg-blue-500 text-white py-2 px-4 rounded-lg"
        >
          Visitar mi Ko-fi
        </a>
        
        <a
          href="https://www.paypal.com/ncp/payment/TV74R9EUSHM3N"
          target="_blank"
          rel="noopener noreferrer"
          className="bg-yellow-500 text-white py-2 px-4 rounded-lg"
        >
          Pagar con PayPal
        </a>

        <a
          href="https://ko-fi.com/s/9d7fb1c87a"
          target="_blank"
          rel="noopener noreferrer"
          className="bg-green-500 text-white py-2 px-4 rounded-lg"
        >
          Comprar un fondo ahora
        </a>
      </div>
    </div>
  );
}

Así, los usuarios podrán acceder a tus enlaces fácilmente desde la página principal.

Si quieres que los enlaces aparezcan en todas las páginas, podrías agregarlos en un header o footer. ¿Quieres que lo haga por ti?

