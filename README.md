
# ARRAY-OPERATIONS


bool searchEle(int a[],int x)

{

  int n=sizeof(a)/sizeof(a[0]);

  for(int i=0;i<10000;i++)

  {

  if(a[i]==x)

  return true;

}

return false;

}

bool insertEle(int a[],int y,int yi)

{

 int n=sizeof(a)/sizeof(a[0]);

 if(yi>=10000)

 return false;

 a[yi]=y;

 return true;

}

bool deleteEle(int a[],int z)

{

 int n=sizeof(a)/sizeof(a[0]);

  for(int i=0;i<n;i++)

  {

if(a[i]==z)

{

for(int j=i;j<n-1;j++)

{

a[i]=a[i+1];

}

return true;

}

  }

return true;

}
