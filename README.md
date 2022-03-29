# Primitive-datatypes-tasks
### PowerShell

#### Task 1 - Use 'Get-Help' to find out more information about 5 cmdlets.

> - Command `Get-Help Get-Help`
>
> ![image](https://user-images.githubusercontent.com/77643882/160606847-28ca9d2d-af14-4497-b14e-b2222f620c0b.png)
>
> ![image](https://user-images.githubusercontent.com/77643882/160606987-3568df61-d310-4fd3-9802-f7fa08c34588.png)
>
> - Command `Get-Help New-Item`
>
> ![image](https://user-images.githubusercontent.com/77643882/160607791-24ca4046-645c-4151-b381-1b508169219a.png)
>
> - Command `Get-Help Get-Alias`
>
> ![image](https://user-images.githubusercontent.com/77643882/160608545-6d9a7694-173f-4d83-a3f8-b29b959ab2b2.png)
>
> - Command `Get-Help Get-AuthenticodeSignature`
>
> ![image](https://user-images.githubusercontent.com/77643882/160608774-ceb9d854-e682-457a-b3ce-52143a94f671.png)
>
> - Command `Get-Help Get-ControlPanelItem`
>
> ![image](https://user-images.githubusercontent.com/77643882/160608940-60622162-b491-426b-8ba9-ed6546179ec4.png)

#### Task 2 - Use 'Get-Help' with the '-Example' parameter for the 5 cmdlets you discovered more about in task 1.

> - Command `Get-Help Get-Help -Examples`
>
> ![image](https://user-images.githubusercontent.com/77643882/160611222-62ee4c64-9740-4823-a6a5-7737df3a96ea.png)
>
> - Command `Get-Help New-Item -Examples`
>
> ![image](https://user-images.githubusercontent.com/77643882/160611431-6d39d5a6-7a63-4178-aa61-cef4b0157d50.png)
>
> - Command `Get-Help Get-Alias -Examples`
>
> ![image](https://user-images.githubusercontent.com/77643882/160611688-23426e97-6f29-4d21-905a-932266ec60cc.png)
>
> - Command `Get-Help Get-AuthenticodeSignature -Examples`
>
> ![image](https://user-images.githubusercontent.com/77643882/160612044-6a5ff59f-3809-4d8b-9c76-ad0dc3f0dadf.png)
>
> - Command `Get-Help Get-ControlPanelItem -Examples`
>
> ![image](https://user-images.githubusercontent.com/77643882/160613459-cdd9363e-be3b-4acc-b12b-f08323aa2fa7.png)

#### Task 3 - Create a new text file named 'TestFile.txt' under C:\Maximo\PowerShell\Workshop1\%USERNAME% .

> - Command `New-Item -Path 'C:\' -Name Heber -ItemType Directory`
> - Command `Get-ChildItem -Recurse`
> 
> ![image](https://user-images.githubusercontent.com/77643882/160616129-67275624-91f3-424a-ba33-906228337881.png)
> 
> ![image](https://user-images.githubusercontent.com/77643882/160617856-cf6c3e60-3b42-419a-8400-3157df4a46a4.png)

#### Task 4 - Populate the text file you created in task 3 with all three datatypes we've covered: 'Boolean','String' and 'Int'.

> - Command `Add-Content -Path .\Heber\PowerShell\Workshop1\%USERNAME%\TestFile.txt -Value True`
> - Command `Get-Content -Path .\Heber\PowerShell\Workshop1\%USERNAME%\TestFile.txt`
>
> - Command `Add-Content -Path .\Heber\PowerShell\Workshop1\%USERNAME%\TestFile.txt -Value "Hello"`
> - Command `Get-Content -Path .\Heber\PowerShell\Workshop1\%USERNAME%\TestFile.txt`
>
> - Command `Add-Content -Path .\Heber\PowerShell\Workshop1\%USERNAME%\TestFile.txt -Value 42`
> - Command `Get-Content -Path .\Heber\PowerShell\Workshop1\%USERNAME%\TestFile.txt`
>
> ![image](https://user-images.githubusercontent.com/77643882/160619791-21f88966-bf26-40ad-bfcd-ed4aa263317e.png)

#### Task 5 - Read from the text file and use 'Get-Member' to find the datatype returned.

> - Command `Get-Content -Path .\Heber\PowerShell\Workshop1\%USERNAME%\TestFile.txt | Get-Member`
>
> ![image](https://user-images.githubusercontent.com/77643882/160622360-653bf55f-1d20-4d46-8fd0-683d9effce86.png)

#### Task 6 - Overwrite all data within the text file that you created in task 3.

> - Command `Set-Content -Path .\Heber\PowerShell\Workshop1\%USERNAME%\TestFile.txt -Value "Follow the white rabbit"`
> - Command `Get-Content -Path .\Heber\PowerShell\Workshop1\%USERNAME%\TestFile.txt`
>
> ![image](https://user-images.githubusercontent.com/77643882/160623302-1d395a44-5f90-400f-a748-37c5b2b12d2c.png)

#### Task 7 - Format the data returned by a cmdlet into a list.

> - Command `Get-Service | Format-List`
>
> ![image](https://user-images.githubusercontent.com/77643882/160624207-3f7c27f6-beff-4970-aa10-9f20a4e6985a.png)

#### Task 8 - Pipe 'Get-Command' into 'Out-GridView'.

> - Command `Get-Command | Out-GridView`
>
> ![image](https://user-images.githubusercontent.com/77643882/160624764-8242461b-0e4e-4e8b-bcbf-34bafacf5a22.png)

#### Task 9 - Pipe the 5 cmdlets you discovered in task 1 into 'Out-GridView'.

> - Command `Get-Help | Out-GridView`
> 
> ![image](https://user-images.githubusercontent.com/77643882/160626001-eb7ce36a-3e05-4218-ba9f-d8456829519a.png)
>
> - Command `Get-Alias | Out-GridView`
>
> ![image](https://user-images.githubusercontent.com/77643882/160626535-f2c98a24-24e5-4c69-bc8a-bd4db6d88cc9.png)
>
> - Command `Get-ControlPanelItem | Out-GridView`
>
> ![image](https://user-images.githubusercontent.com/77643882/160626964-c974cf42-a9a2-4e00-b727-40800bf92d53.png)

>
>
>
>




























