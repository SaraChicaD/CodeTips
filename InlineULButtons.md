<ul class="list-unstyled list-inline">
    <li ng-if="viewmodel.repository">
        <button ng-click="actions.import()" class="btn btn-primary">{{'Import'|translate}}</button></li>
    <li ng-if="viewmodel.repository">
        <p class="form-control-static">{{'Repo'|translate}}: {{viewmodel.repository.path}}</p></li>
    <li ng-if="viewmodel.repository">
        <button ng-click="actions.editRepository()" class="btn btn-link">{{'Edit'|translate}}</button></li>
    <li ng-if="!viewmodel.repository">
        <button ng-click="actions.editRepository()" class="btn btn-primary">{{'Create'|translate}}</button></li>
    <li class="pull-right" ng-if="viewmodel.repository">
        <p class="form-control-static">{{'Repo'|translate}}: {{viewmodel.repository.availableSpace}}</p>
    </li>
</ul>