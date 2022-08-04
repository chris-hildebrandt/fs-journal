# MVC

Jeopardy notes:
get axiosService script tag by autofilling the script:axios in html then make an AxiosService.js you export const = new axios.create ({
  baseURL: "" 
})

when getting an object from an API, log the "res.data" and look at that object in the console to figure out what data you want to use.
shift+alt+down arrow copies line and places it below.

if there is no change in data, there may not need to be an extra model/controller/service jeopardy kept the "player" mvc pattern for active and listed players, because the objects did not change from being in the list to being active.

async is only necessary when you are using a server. setting active player in jeopardy was not made async because it was just using local data.

if (!something){
  return
} this defeats the variable might be bad intellisense always log when creating a new controller to see that it is wired up it is also good to use on non async functions with internal prerequisites. 

to pass a query on your res ('/url', {params{}})

place modals in the html under the footer

modal closing add data-bs-dismiss to anything that you want to close the modal

.put to edit res = await aliasApi.put(`/address/${ProxyState.object.id}`, ProxyState.object) console.log the res.data!!
ProxyState.object = new Class(res.data)

.get to create

.delete to delete

.

