DIVERSITY & INCLUSION DASHBOARD

Kpi:
  Number of Men   = COUNTROWS(FILTER('03 Diversity-Inclusion-Dataset xlsx - Pharma Group AG', '03 Diversity-Inclusion-Dataset xlsx - 
                                  Pharma Group AG'[Gender] = "Male"))

  Number of Women = COUNTROWS(FILTER('03 Diversity-Inclusion-Dataset xlsx - Pharma Group AG', '03 Diversity-Inclusion-Dataset xlsx - Pharma Group AG'
                    [Gender] = "Female"))

  Number of Leavers = COUNTROWS(FILTER('03 Diversity-Inclusion-Dataset xlsx - Pharma Group AG', '03 Diversity-Inclusion-Dataset xlsx - Pharma Group AG'
                      [FY20 leaver?] = "Yes"))

  Promoted Employees FY21 = COUNTROWS(FILTER('03 Diversity-Inclusion-Dataset xlsx - Pharma Group AG','03 Diversity-Inclusion-Dataset xlsx - Pharma Group AG'
                            [Job Level After FY21 Promotions] <> '03 Diversity-Inclusion-Dataset xlsx - Pharma Group AG'[Job Level Before FY20 Promotions]))

 Turnover FY20   = DIVIDE([Number of Leavers], [Total Employees], 0)

 Percent Women Promoted = DIVIDE([Women Promoted FY21], [Number of Women] , 0)

Charts:
 1) Employee Demographics
 2) Time in Job Level and Department
 3) Job Levels and Promotions
 4) Miscellaneous
 5) Hiring and Turnover
 6) Performance and Ratings

Charts used : Line chart , Donut chart , Stacked column chart , Stacked bar chart

