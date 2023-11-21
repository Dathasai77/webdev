# webdev
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>REGISTRATION FORM</title>
        <script src="https://cdn.tailwindcss.com"></script>
    </head>
    
    <body style="background-color: rgb(250, 148, 31)">
        <div class="relative py-8 justify-center">
            <div
            class="relative bg-white px-6 pt-5 pb-5 shadow-xl ring-gray-900/5 sm:mx-auto sm:max-w-lg sm:rounded-lg sm:px-10">
            <div class="mx-auto -w-md">
                <h1 class="text-center font-bold text-4xl  ">
                    REGISTRATION FORM
                </h1>
                <div class="divide-y divide-gray-300/50">
                    <div class="space-y-6 py-8 text-base leading-7 text-gray-600">
                        <form id="user-form">
                            <label for="name" class="text-md w-40 inline-block font-medium leading-5 text-gray-700">
                                NAME*
                            </label>
                            <input required type="text" id="name" name="name" class="bg-gray-100 inline-block rounded-lg shadow-md px-4 py-3 mb-5 text-base leading-6 placeholder-gray-500 focus :invalid:border-pink-500 focus:invalid:ring-pink-500"
                            placeholder="ENTER FULL NAME"></br>

                            <label for="email" class="text-md w-40 initial-block font-medium leading-5 text-gray-700">
                                EMAIL*     
                            </label>
                            <input required type="email" id="email" name="email" style="margin-left:120px" class="bg-gray-100 inline-block rounded-lg shadow-md px-4 py-3 mb-5 text-base leading-6 placeholder-gray-500
                            focus:invalid:border-pink-500 focus:invalid:ring-pink-500" placeholder="ENTER EMAIL" ></br>
                            <label for="password" class="text-md w-40 inline-block font-medium leading-5 text-gray-700">
                               PASSWORD*
                            </label>
                            <input required type="password" id="password" name="password" class="bg-gray-100 inline-block rounded-lg shadow-md px-4 py-3 mb-5 text-base leading-6 placeholder-gray-500
                            focus:invalid:border-pink-500 focus:invalid:ring-pink-500"
                            placeholder="ENTER PASSWORD" ></br>
                            <label for="dob" class="text-md w-40 inline-block font-medium leading-5 text-gray-600">
                                DATE OF BIRTH*
                            </label>
                            <input required type="date" id="dob" class="bg-gray-100 inline-block rounded-lg shadow-md px-4 py-3 mb-5 text-base leading-6 placeholder-gray-500
                            focus:invalid:border-pink-500 focus:invalid:ring-pink-500" ></br>
                            <label for="acceptTerms"
                            class="text-md w-50 inline-block font-medium leading-5 text-gray-700">
                            ACCEPT TERMS AND CONDITIONS
                            </label>
                            <input required type="checkbox" id="acceptTerms" name="acceptTerms"
                            class="bg-gray-100 inline-block rounded-lg shadow-md px-4 py-3 mb-5 text-base leading-6 placeholder-gray-500 focus:placeholder-gray-500"></br>
                            <button type="submit"
                            class="w-fit rounded-lg shadow-md px-8 py-4 bg-blue-500 text-white hover:bg-blue-400 focus:outline-none focus:shadow-outline tansition" 
                            onclick="checkAgeValidity()">SUBMIT</button>
                           </form>
                        </div>
                    </div>
                 </div>
            </div>
        </div>

        <div  class="relative bg-gray px-6 pt-10 pb-8 shadow-xl ring-1 ring-gray-900/5 sm:mx-auto sm:rounded-lg sm:px-10">
            <div class="mx-auto">
                <h2 class="text-3xl text-center font-bold leading-tight"> Entries</h2>
                <div class="divide-y divide-gray-300/50 py-3" id="user-entries"></div>

            </div>
        </div>
