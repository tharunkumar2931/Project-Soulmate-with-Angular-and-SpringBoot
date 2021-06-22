 FROM node:14.15.4
 RUN mkdir -p /usr/src/app
 WORKDIR /usr/src/app
 COPY package.json /usr/src/app
 RUN npm install
 COPY . /usr/src/app
 EXPOSE 4200
 CMD ["npm", "start"]


<!-- <div class="container">
    <div class="row">
        <div class="col-md-6 offset-md-3" style="justify-content: center;margin-top: 5px; ">

            <a class="nav-link" class="btn btn-success" style="border-radius: 10px;margin-left: 45px;"
                routerLink="/doctorconsultant">Doctor
                Consultant</a>

            <a class="nav-link" class="btn btn-primary" style="border-radius: 10px;margin-left: 15px; "
                routerLink="/plasmadonar">
                Blood Plasma Donar</a>

            <a class="nav-link" class="btn btn-success" style="border-radius: 10px; margin-left: 15px;"
                routerLink="/">Medical
                Request</a>
        </div>



            <div class="col-md-4 offset-md-4"
                style="border: black;border-width: 1px;border-style: solid;margin-top: 10px;padding :5px"
                *ngIf="!condition;">
                <form [formGroup]="donarForm" (ngSubmit)="onSubmit()">

                    <div class="mt-4">

                        <input id="name" type="text" formControlName="name" class="form-control"
                            placeholder="Patient Name">
                        <div class="text-danger" *ngIf="name.dirty && name.invalid">
                            Name is required
                        </div>
                    </div>

                    <div class="mt-3">

                        <input id="age" type="number" formControlName="age" [pattern]="" placeholder="Age"
                            class="form-control">
                        <div class="text-danger" *ngIf="age.dirty && age.invalid">
                            Age is incorrect
                        </div>
                    </div>

                    <div class="mt-3">

                        <input id="bloodgroup" type="text" formControlName="bloodgroup" [pattern]="donar"
                            class="form-control" placeholder="Bloodgroup">
                        <div class="text-danger" *ngIf="bloodgroup.dirty && bloodgroup.invalid ">
                            BloodGroup is not valid
                        </div>
                    </div>

                    <div class="mt-3">

                        <input id="hospitalname" type="text" formControlName="hospitalname" class="form-control"
                            placeholder="Hospital Name">
                        <div class="text-danger" *ngIf="hospitalname.dirty && hospitalname.invalid">
                            Hospital Name is required
                        </div>
                    </div>

                    <div class="mt-3">

                        <input id="hospitaladdress" type="text" formControlName="hospitaladdress" class="form-control"
                            placeholder="Hospital Address">
                        <div class="text-danger" *ngIf="hospitaladdress.dirty && hospitaladdress.invalid">
                            Hospital Address is required
                        </div>
                    </div>

                    <div class=mt-3>
                        <h4>UploadPrescription</h4>
                        <div class="container row">
                            <div class="col-md-6 mr-3">
                                <input type="file" (change)="onFileChanged($event)"
                                    formControlName="uploadPrescription">
                            </div>
                            <div class="col-md-6 mb-3">
                                <input type="button" (click)="onUpload()" value="upload">
                            </div>
                        </div>
                    </div>


                    <div class="mt-3">
                        <button id="btnsubmit" class="btn btn-secondary"
                            style="margin-left: 150px; margin-bottom: 10px;">Submit</button>
                    </div>
                </form>

            </div>
            <div *ngIf="condition;">
                <mat-card class="example-card">
                    <mat-card-header>
                        <mat-card-title> Your Blood Donar </mat-card-title>
                    </mat-card-header>
                    <mat-card-content>
                        <div class="details">
                            <h3>DonarName:</h3>
                            <h3>Contact number:</h3>
                            <h3>Email Id:</h3>
                        </div>
                    </mat-card-content>
                </mat-card>

            </div>
        </div>
    </div> -->



