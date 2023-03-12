<script>
	import { currentUser } from '$lib/pocketbase';
</script>

{#if $currentUser}
	<div class="flex justify-center">
		<label for="my-modal-4" class="btn-primary btn">Create post</label>
		<input type="checkbox" id="my-modal-4" class="modal-toggle" />
		<label for="my-modal-4" class="modal cursor-pointer">
			<label class="modal-box relative" for="">
				<h3 class="text-lg font-bold">Create post</h3>
			</label>
		</label>
	</div>
{/if}

kat
