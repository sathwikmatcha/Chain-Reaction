# Chain-Reaction
echo "# Chain-Reaction" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/sathwikmatcha/Chain-Reaction.git
git push -u origin master
#this is a code for a game called Chain Reaction

include struct point1{int x;int y;}; struct point{int x;int y;char a;}; main_program{ int m;int n;int np;int cnt=0;int x,y;char a; cin>>m>>n>>np; int cr[m][n]; for(int i=0;i<m;i++){for(int j=0;j<n;j++){cr[m][n]=0;}}

while(x >=0 or y >=0){
    cin>>x>>y;
    cnt++;
    if(np==2)
    {if(cnt%2==1){a='R';}
     else {a='G' ;}    
    }
    if(np==3){
        if(cnt%3==1){a='R';}
        if(cnt%3==2){a='G';}
        if(cnt%3==0){a='B';}
    }
    if(np==4){
        if(cnt%4==1){a='R';}
        if(cnt%4==2){a='G';}
        if(cnt%4==3){a='B';}
        if(cnt%4==0){a='Y';}
    }
    if(np>4 or np<2)
        {cout<<"please take number of players less than or equal to 4"<<endl;}
    if(x>=m or y>=n){cout<<"Illegal Move"<<endl;cnt--;}
    if(x<m and y<n){cr[x][y]++;
}
}
