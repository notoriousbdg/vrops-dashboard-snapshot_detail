# Snapshot Detail Dashboard for vRealize Operations 8.2 and Cloud
---------

View detailed info for all VM snapshots using [vRealize Operations](https://www.vmware.com/products/vrealize-operations.html).

## Dashboard
![Snapshot Detail](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-snapshot_detail/master/images/Dashboard.png)

## Installation
1. Edit the Policy at `Administration` / `Policies` / `Policy Library`.  The policy should be `vSphere Solution's Default Policy (DATE)` unless a new policy was explicitly created.  
![Policy Library](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-snapshot_detail/master/images/Policy_Library.png)
2. Enable `Disk Space|Snapshot|Creator` and `Disk Space|Snapshot|Description` metrics for Virtual Machine objects  
![Policy Metrics](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-snapshot_detail/master/images/Policy_Metrics.png)
3. Import the view at `Dashboards` / `Views` / `Import...`  
![Import View](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-snapshot_detail/master/images/Import_View.png)
4. Click `Browse...` then select the file named [Views.zip](https://github.com/notoriousbdg/vrops-dashboard-snapshot_detail/raw/master/Views.zip)
5. Import the dashboard at `Dashboards` / `Actions` / `Manage Dashboards` / `Import Dashboards`  
![Import Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-snapshot_detail/master/images/Import_Dashboard.png)
6. Click `Browse...` then select the file named [Dashboards.zip](https://github.com/notoriousbdg/vrops-dashboard-snapshot_detail/raw/master/Dashboards.zip)
7. The dashboard should now be available in in the dashboard list  
![Dashboard List](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-snapshot_detail/master/images/Dashboard_List.png)

## Dashboards
| Dashboard Name | Dashboard Path |
|--|--|
| Snapshot Detail | Shared Dashboards (GBrandon)/Troubleshooting |

## Views
| View Name | Name on Dashboard | View Type |
|--|--|--|
| Snapshot Detail | Snapshot Detail | List |

## Support

This dashboard requires vRealize Operation 8.2 Advanced or Enterprise edition or vRealize Operations Cloud.

The older version, which is compatible with vRealize Operations 6.7, 7.0, 7.5, 8.0, and 8.1 is available [here](https://github.com/notoriousbdg/vrops-dashboard-snapshot_detail/tree/vrops-8.1).

Please open an [issue](https://github.com/notoriousbdg/vrops-dashboard-snapshot_detail/issues) for feedback.

## Changelog
2018-09-26
* Initial release

2018-11-19
* Added vRealize Operations 7.0 support

2019-02-11
* Added datastore column

2019-04-30
* Added vRealize Operations 7.5 support

2019-10-24
* Added vRealize Operations 8.0 support

2020-11-09
* Updated to support vRealize Operations 8.2
* Addressed issues https://github.com/notoriousbdg/vrops-dashboard-snapshot_detail/issues/7 and https://github.com/notoriousbdg/vrops-dashboard-snapshot_detail/issues/8
* The previous version for vRealize Operations 6.7, 7.0, 7.5, 8.0, and 8.1 is available [here](https://github.com/notoriousbdg/vrops-dashboard-snapshot_detail/tree/vrops-8.1)