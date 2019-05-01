# Snapshot Detail Dashboard for vRealize Operations 6.7, 7.0, and 7.5
---------

View detailed info for all VM snapshots using [vRealize Operations](https://www.vmware.com/products/vrealize-operations.html).

![Snapshot Detail](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-snapshot_detail/master/Dashboard.png)


## Installation
1. Edit the Policy at `Administration` / `Policies` / `Policy Library`.  The policy should be `vSphere Solution's Default Policy (DATE)` unless a new policy was explicitly created.  
![Policy Library](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-snapshot_detail/master/Policy_Library.png)
2. Enable `Disk Space|Snapshot|Creator` and `Disk Space|Snapshot|Description` metrics for Virtual Machine objects  
![Policy Metrics](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-snapshot_detail/master/Policy_Metrics.png)
3. Import the view at `Dashboards` / `Views` / `Import...`  
![Import View](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-snapshot_detail/master/Import_View.png)
4. Click `Browse...` then select the file named [View - Snapshot Detail.zip](https://github.com/notoriousbdg/vrops-dashboard-snapshot_detail/raw/master/View%20-%20Snapshot%20Detail.zip)
5. Import the dashboard at `Dashboards` / `Actions` / `Manage Dashboards` / `Import Dashboards`  
![Import Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-snapshot_detail/master/Import_Dashboard.png)
6. Click `Browse...` then select the file named [Dashboard - Snapshot Detail.zip](https://github.com/notoriousbdg/vrops-dashboard-snapshot_detail/raw/master/Dashboard%20-%20Snapshot%20Detail.zip)
7. The dashboard should now be available in in the dashboard list  
![Dashboard List](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-snapshot_detail/master/Dashboard_List.png)


## Support

This dashboard requires vRealize Operation 6.7, 7.0, or 7.5 Advanced or Enterprise edition.

Please open an [issue](https://github.com/notoriousbdg/vrops-dashboard-snapshot_detail/issues) for feedback.
