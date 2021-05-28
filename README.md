<h1> Refresh Region Display Selector Regions - Oracle APEX Dynamic Action Plugin</h1>

<h2>Uses</h2>
The plugin can be used for refreshing the regions under the Region Display Selector.<br>
Multiple regions can be refreshed.
  
<h2>Installation</h2>
Import plugin file "dynamic_action_plugin_refresh_rds_region.sql" from Source directory into your application.

<h2>How to Use</h2>
1) Create a Dynamic Action (Event: Page Load).<br>
2) Create a True action.<br>
3) Select the Refresh Region Display Selector Region [Plug-in] option.<br>
4) Provide the Static ID of the region that you want to refresh that is under the Region Display Selector.<br>
   If multiple regions has to be refreshed please provide the Static ID of the regions separated by comma.<br>
   <b>Example:</b> EMP,DEPT<br><br>
   
<h2>Image Reference</h2>
https://user-images.githubusercontent.com/30211230/119977762-6eef1180-bfd6-11eb-90f8-97638252c1c1.png
   
   
<h2>Demo</h2>
https://apex.oracle.com/pls/apex/workspace_akil/r/demo/refresh-rds-region-plug-in
