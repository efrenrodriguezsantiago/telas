/*calcular el costo de produccion de una prenda tomando en cuenta
los siguientes datos
- numero de metros de tela utilizados
- costo por metro
- importe total de accesorios utilizados
calcular el costo de produccion,
 la ganancia (0.30)
y el costo de la venta por prenda
*/

#include<iostream>
using namespace std;
int main()
{
	int m_tela,c_metro,i_accesorios,produccion,ganancia,v_prenda; 
	
	cout<<"\n               introduce el metro de tela utilizado :";cin>>m_tela;
	
	cout<<"\n               introduce el costo por metro:";cin>>c_metro;
	
	cout<<"\n               introduce el importe total de accesorios:";cin>>i_accesorios;
	
	produccion = m_tela * c_metro + i_accesorios;
	
	cout<<"\n               el costo de produccion es :"<<produccion;
	
	ganancia = produccion * 0.30;
	
	cout<<"\n               el costo de la ganancia es:"<<ganancia;

	v_prenda = produccion + ganancia;
	
	cout<<"\n               el costo dela venta por la prenda es:"<<v_prenda;
	
	return 0;
}
