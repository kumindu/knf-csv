# knf-csv
knf csv application

Copyright (C) 2018 KUMINDU INDURANGA RANAWAKA This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.
 
 
        KnfCsvReader KNF=new KnfCsvReader();
        
        KNF.READ_FILE_PATH="C:\\test_Read.csv";
        KNF.WRITE_FILE_PATH="C:\\test_write.csv";
        KNF.NUMBER_OF_RECORDS=5;
        
        String [][] arr= KNF.Reader();
        String [] Header ={"app","sds","sdas","sads"};
        String [] Values ={"","",""};
        KNF.Writer(Header,Values);
