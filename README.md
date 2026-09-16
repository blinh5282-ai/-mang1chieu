# -mang1chieu
void M1C::chenk(int k){
	int x;
	cout<<"Nhap gia tri can chen: ";
	cin>>x;
	cout<<"Nhap vi tri can chen: ";
	cin>>k;
	if(k<0||k>n){
		cout<<"Vi tri xoa khong hop le!";
		return;
	}
	for(int i=n; i>k; i--){
		a[i]=a[i-1];
	}
	a[k]=x;
	n++;
	cout<<"Mang sau khi chen la:";
}
