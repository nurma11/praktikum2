# praktikum2
# Latihan 1 membuat penentuan terbesar dari 3 bilangan.
	mendeklarasikan variabel int a,b,c sebagai variabel input
	menginputkan nilai a,b,c
	membandingkan nilai a,b,c dengan rumus if berikut kodenya
	if (A>B){
        		if (A>C)
           		 cout<< "Bilangan Terbesar Adalah :" << A;
        		else
          		cout<< "Bilangan Terbesar Adalah :" << C;
        	}else{
        		if ( B>C )
            		cout << "Bilangan Terbesar Adalah:" << B;
       			 else
            		cout << "Bilangan Terbesar Adalah:" << C;
ini hasilnya 
![img](https://github.com/nurma11/praktikum2/blob/master/latihan1/WhatsApp%20Image%202019-01-26%20at%2001.31.22.jpeg)

# Latihan2 membuat penentuan terbesar dan terkecil dari 4 variabel. -Mendeklarasikan variabel n,nilai sebagai variabel input -Mendeklarasikan variabel i sebagai pembatas inputan/perulangan -Mendeklarasikan max sebagai nilai terbesar dan min nilai terkecil -Menginputkan nilai n dimana menunjukan banyak angka yang akan di input -menginputkan nilai nilai yang akan di bandingkan. Berikut kode lengkapnya

	int i,n,max,min,nilai;

    cout<<"===Menentukan Bilangan Terbesar & Terkecil==="<< endl;
    cout<<"Masukan Banyak Bilangan:";
    cin>> n;
    cout<<"Masukan Nilai ke =";
    cin>> nilai;

    max=nilai;
    min=nilai;

    for(i=2;i<=n;i++) //dapat dibaca i akan membaca di nilai ke2 dimana i kurang dari samadengan n,i akan menambah 1 angka dan seterusnya.
    {

        cout<<"Masukan Nilai Ke"<<i<<"=";
        cin>>nilai;

        if (nilai>max) max=nilai;
        if (nilai<min) min=nilai;
    }
    cout<<"Nilai Terbesar Adalah:" <<max<<"\nNilai Terkecil Adalah:"<<min;
Ini Hasilnya 
![img](https://github.com/nurma11/praktikum2/blob/master/latihan2/WhatsApp%20Image%202019-01-26%20at%2001.31.22%20(1).jpeg)

