<td>
   <span ng-if="row.health == 'green'"><i class="ci ci ci-nav-ok-core text-success"></i></span>
   <span ng-if="row.health == 'yellow'"><i class="ci ci-status-warn-core text-warning"></i></span>
   <span ng-if="row.health == 'red'"><i class="ci ci-status-critical-core text-danger"></i></span>
   <span ng-if="row.health == 'trash'"><i class="ci ci-delete-trash-core text-primary"></i></span>
</td>