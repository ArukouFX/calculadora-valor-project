--//Español//--

Calculadora de Interés Compuesto en React

Este proyecto es una aplicación de calculadora de interés compuesto basada en React. Permite a los usuarios ingresar un depósito inicial, contribución anual, número de años y tasa de interés para calcular el saldo final.
Componentes

    Input: Un campo de entrada de formulario que permite a los usuarios ingresar valores para el depósito inicial, contribución anual, número de años y tasa de interés.
    Button: Un botón que los usuarios pueden hacer clic para enviar el formulario y calcular el saldo final.
    Container: Un contenedor que contiene el formulario y la visualización del saldo final.
    Section: Una sección que separa el formulario y la visualización del saldo final.
    Balance: Una visualización que muestra el saldo final después del cálculo.

Funcionamiento

    El usuario ingresa valores para el depósito inicial, contribución anual, número de años y tasa de interés en los campos de entrada del formulario.
    El usuario hace clic en el botón "Calcular" para enviar el formulario.
    La aplicación utiliza la función compoundInterest para calcular el saldo final basado en los valores de entrada.
    Se muestra al usuario el saldo final.

Estado

    balance: Una cadena que contiene el saldo final después del cálculo.

Métodos

    compoundInterest: Una función que toma un depósito inicial, contribución anual, número de años y tasa de interés y devuelve el saldo final.
    handleSubmit: Una función que se llama cuando se envía el formulario. Toma los valores del formulario y llama a la función compoundInterest para calcular el saldo final.
    render: Renderiza la aplicación.

Importante

    El código está estructurado con React Hooks y la librería Formik.
    La aplicación utiliza Intl.NumberFormat para dar formato al saldo final como una moneda.
    La aplicación utiliza Yup para validar los inputs.
    El componente App es el componente principal que se exporta para ser utilizado en otro archivo.

--//English//--

Compound Interest Calculator in React

This project is a compound interest calculator application based on React. It allows users to input an initial deposit, annual contribution, number of years, and interest rate to calculate the final balance.
Components

    Input: A form input field that allows users to enter values for the initial deposit, annual contribution, number of years, and interest rate.
    Button: A button that users can click to submit the form and calculate the final balance.
    Container: A container that holds the form and final balance display.
    Section: A section that separates the form and final balance display.
    Balance: A display that shows the final balance after calculation.

Functionality

    The user enters values for the initial deposit, annual contribution, number of years, and interest rate in the form input fields.
    The user clicks the "Calculate" button to submit the form.
    The application uses the compoundInterest function to calculate the final balance based on the input values.
    The final balance is displayed to the user.

State

    balance: A string that contains the final balance after calculation.

Methods

    compoundInterest: A function that takes in an initial deposit, annual contribution, number of years, and interest rate and returns the final balance.
    handleSubmit: A function that is called when the form is submitted. It takes in the form values and calls the compoundInterest function to calculate the final balance.
    render: Renders the application.

Important

    The code is structured with React Hooks and Formik library.
    The application uses the Intl.NumberFormat to format the final balance as a currency.
    The application use Yup for validate the inputs.
    The App component is the main component that is exported to be used in another file.