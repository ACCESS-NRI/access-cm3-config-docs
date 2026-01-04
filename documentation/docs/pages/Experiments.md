
<!-- some hacks to hide the table of contents and make the links sidebar smaller, 
so the table has more screen real estate -->
<style>
.md-sidebar--secondary:not([hidden]){
  display: none 
}

.md-sidebar {
    width: 8rem
}

</style>

# ACCESS-CM3 Experiments

The below lists key experiments that are being used to improve, evaluate and drive development for CM3. We welcome scientific and technical feedback on these runs. If you would like to get involved in evaluation of these runs, see instructions [here](https://github.com/acCESS-Community-Hub/access-cm3-paper-1/) and an overview [here](/contributing/#help-us-evaluate-and-improve-applications-of-cm). 

The below data is from unreleased configurations, they will not be kept long-term and will be deleted when newer control experiments are completed.

This data, and the configurations they are based on, are licensed by 
[CC-by-4.0](https://creativecommons.org/licenses/by/4.0/) and therefore can be freely shared, 
distributed and modified. Users of ACCESS-NRI models, data, tools or expert support are required
 to clearly include an [acknowledgement](https://www.access-nri.org.au/resources/acknowledging-us/)
  in all publications/reports/public releases.

| Experiment | Base Configuration | Date completed | Description                                                                                                                                                                                                                                                                                                                                        | Model build                                                                                                                    | Length (years) | ESM Datastore  <br/>  (output path) |
| ---------- | ------------------ | -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ | -------------- | --------------------------- |
|            |                    |                | CM3 25km ocean which is a present day control with constant forcing (year numbers are essentially meaningless). This run is not made from a released configuration/build so there is no guarantees of it being available or re-producible long-term. Ocean initial conditions are taken from a "cold start" in ACCESS-OM3 (e.g., WOA2023 January). | \`/g/data/zv30/non-cmip/ACCESS-CM3/cm3-run-11-08-2025-25km-beta-om3-new-um-params/cm3-demo-datastore/cm3-demo-datastore.json\` |

# ACCESS-CM2 Experiments

The below list are key CM2 experiments that are being used to improve, evaluate and drive development for CM3. When evaluating CM3 we encourage comparisons between CM2 and CM3. 

| Experiment | Base Configuration | Date completed | Description                                                                                                                                                                                                         | Model build                      | Length (years) | ESM Datastore <br/> (output path) |
| ---------- | ------------------ | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------- | -------------- | --------------------------- |
|            |                    |                | CM2 25km present day control run for comparison. Again year numbers are meaningless but in this case start from "1". We recommend comparing the first N years of this run to ACCESS-CM3 runs to assess the spin-up. | (\`/g/data/lg87/wgh581/cz861/\`) |
