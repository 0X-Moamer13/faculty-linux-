The first thing و I get a root permission  and after that , i created a directory called FACULTY and it has a 2 subdirectories , The first subdirectory has a 3 files fac1,fac2,fac3.

![Screenshot from 2021-04-24 20-07-35](https://user-images.githubusercontent.com/77538165/116014794-e1da2680-a5eb-11eb-977c-818575f39573.png)

 
And in this screenshot Copy the content of fac1 file to the second subdirectory by "cp" command. 

![S146-49](https://user-images.githubusercontent.com/77538165/116015728-359a3f00-a5ef-11eb-804c-b1a5e0a5aa88.png)

In the third screenshot , i crated file called ali.txt to has the content of the dispaly of number of users and the output will  be 1 who is me. 
and file2.txt will has a content of the display of number of files. 
and the files that have a or A . 


![Screenshot from 2021-04-26 02-17-16](https://user-images.githubusercontent.com/77538165/116017274-04703d80-a5f4-11eb-8aae-e9c804ff0559.png)

no files in directory begain with a or A

![2](https://user-images.githubusercontent.com/77538165/116131076-ca994880-a680-11eb-88cb-79f54a41344a.png)


The Program :

#include <stdio.h>

int main()

F *f;
int lines_n=0;

char filename[100],sample_;

printf("Enter file name");

scanf("%s" , filename);

F=fopen("%s" , filename , "r");


sample_chr = getc(fp);

    while (sample_!= EOF) {
    
        
        if (sample_ == '')
        {    
            
            ines_n=no_lines+1;
        }
        
        sample_= getc(F);
    }
    fclose(F); //close file.
    printf("There are %d lines in %s 
    ", no_lines, filename);
    return 0;
}
