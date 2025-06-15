import React from 'react';
import Header from './components/Header';
import Home from './components/Home';
import OrderForm from './components/OrderForm';

function App() {
  return (
    <div>
      <Header />
      <main className="p-4">
        <Home />
        <OrderForm />
      </main>
    </div>
  );
}

export default App;
